# STP-Parti-Bitwuzla at SMT-COMP 2025

We intend to participate in the forthcoming SMT-COMP 2025 by submitting **STP-Parti-Bitwuzla** for **the Parallel Track** and **the Cloud Track** categories.

**STP-Parti-Bitwuzla** is a **wrapper** tool based on STP and Bitwuzla, and intend for **QF_BV**. The authors of **STP-Parti-Bitwuzla** are **Mengyu Zhao, Zhenghang Xu, Jinkun Lin, and Shaowei Cai**.

The system description is named `STP_Parti_Bitwuzla_at_SMT_COMP_2025.pdf`.

As per the submission rule, we are providing the pseudo-random 32-bit unsigned number **998244353**.

Zenodo DOI: 10.5281/zenodo.15640498

## Variable-level Partitioning for Distributed SMT Solving

STP-Parti-Bitwuzla is the practical implementations of our innovative concept of **Var**iable-level **Parti**tioning, which is applied to the Bit-Vectors theory. This technique is introduced for the first time in our recently published paper at CAV 2024, titled *Distributed SMT Solving Based on Dynamic Variable-level Partitioning*. 

Our proposed variable-level partitioning permits robust, comprehensive partitioning. Regardless of the Boolean structure of any given instance, our partitioning algorithm can keep partitioning to the last moment of the solving process.

Compared to STP and Bitwuzla, STP-Parti-Bitwuzla innovates in the following aspects:
 - Dynamic distributed framework.
 - Integration of term-level and variable-level partitioning.        
 - Enhanced preprocessing and constraint propagation for the BV theory.
 - A load balancing mechanism for enhanced parallel solving efficiency.

## How to Build and Test

Download solver binary files in Zenodo.

Test in the instance:
```bash
./STP-Parti-Bitwuzla-at-SMT-COMP-2025-build/solver/run_BVParti.py ./STP-Parti-Bitwuzla-at-SMT-COMP-2025-build/test-instances/bv-unsat-3.05.smt2 64
```
