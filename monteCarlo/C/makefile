all: monteCarloIntegrate

include ../../Makefile.in

# makefile for Monte Carlo Kernels
# Alex Kaiser, LBNL, 9/2010



monteCarloIntegrate: monteCarloIntegrate.o
	$(CC) monteCarloIntegrate.o $(CFLAGS) $(CLIBS) -o monteCarloIntegrate $(LDFLAGS)

monteCarloIntegrate.o:
	$(CC) $(CFLAGS) monteCarloIntegrate.c -c

clean:
	rm -f *.o monteCarloIntegrate
