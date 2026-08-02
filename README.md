# Wingraph for Virtual Pascal

This is a port of Stefan Berinde's Wingraph unit for fpc/Delphi7 to Virtual Pascal 2.1.279.  
Original source is here: https://math.ubbcluj.ro/~sberinde/wingraph/

Target OS: Windows (32/64 bits).

The wingraph unit is especially handy for vector graphics but it has an OpenGL interface as well.

Some changes resulting from VP (Virtual Pascal) limitations:
- VP does not recognize out; use var instead 
- VP will not handle dynamic arrays; use fixed arrays instead
- VP will not handle empty parameter lists (); remove the () pair.

In addition many renames from types and interfaces to Windows.

Some relevant compiler options:
- enable Extended syntax
- enable Delphi syntax.

With a new VP install the initial settings are fine.

Demo.pas linker option: set to Compatible with GUI.
