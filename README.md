This repository contains several scripts I wrote for my work.

extract_code.pi:
 This Picat script extracts code snippets enclosed by begin{verbatim} and end{verbatim} in latex files.

flatten_dir.pi:
 This Picat script recursively copies all the plain files under the current directory to the current directory.

gen_solve_all.pi:
 This Picat script generates a command line for executing each Picat file under the current directory.

grade.pi:
 This Picat script processes test scores and produces final grades.

spacing_c.pi:
 This program transforms C program files to enforce spacing rules.
 
extract_solved.pi
 This Picat script processes a log file of a MiniZinc run by PicatSAT, and classifies instances into Solved, NotSolved, and NotCompiled.

gen_conv.pi
 This Picat script generates a command line for converting each MiniZinc benchmark and each "dzn" instance into a FlatZinc file.

gen_solve_all_fzn.pi
 This Picat script generates a command line for executing each FlatZinc file under the current directory.
