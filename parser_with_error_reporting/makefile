default:
	rm -f Newl.hs
	rm -f Scanner.hs
	alex Scanner.x
	happy Newl.y
	ghc -o newl Scanner.hs Newl.hs

clean:
	rm -f *.hs
	rm -f *.hi
	rm -f *.o
	rm -f newl
