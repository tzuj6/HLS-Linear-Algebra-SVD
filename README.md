Linear Algebra Library: SVD
======================================

## 1. OVERVIEW

Implementing the math function SVD from the Linear Algebra  

## 2. SOFTWARE TOOLS AND SYSTEM REQUIREMENTS

Any Vivado HLS release from 2014.1 to 2016.1

## 3. DESIGN FILE HIERARCHY
```
	
	|   README.md
	\---code
			svd.h
		    svd.cpp
		    svd_tb.cpp
	\---code-opt
			svd.h
		    svd.cpp
		    svd_tb.cpp
			hls_svd.h
	\---impl
			svd_top_csynth.rpt
	\---script
			script.tcl
			
```

## 4. INSTALLATION AND OPERATING INSTRUCTIONS

1. In the Vivado HLS command line window:

```
	vivado_hls script.tcl
```

## 5. OTHER INFORMATION

For more information check here: 
[Full Documentation][]
[Vivado HLS User Guide][]

## 6. SUPPORT

For questions and to get help on this project or your own projects, visit the [Vivado HLS Forums][]. 


REF: https://github.com/Xilinx/HLx_Examples
