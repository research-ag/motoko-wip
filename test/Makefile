MOC=moc
VESSEL_PKGS=$(shell vessel sources)

all: llrbtree

llrbtree:
	$(MOC) $(VESSEL_PKGS) -wasi-system-api LLRBTreeTest.mo && wasmtime LLRBTreeTest.wasm
