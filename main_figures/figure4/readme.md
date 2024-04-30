Two-excitation QST in 3x3 and 6x6 qubit networks.

----------------
| Independents |
----------------
t           : evolution time (ns)
dx          : plotting x-coordinate of the distance in Fock space
dy          : plotting y-coordinate of the distance in Fock space
r           : ratio of adjacent gaps

--------------
| Dependents |
--------------                                
prob        : probabilities of qubits
dist        : average distance in the Fock space
fid         : fidelity for Bell-state QST
pr          : distribution of r

-------------
| Constants | 
-------------  
Jcs         : measured NN couplings, J_n,n+1
Jxs         : measured cross couplings, J^x_m,m'
mt_bound    : normalized quantum speed limit bound (MT), t_deltaE=mt_bound/J
dist_max    : maximum distance of Fock space states
dist_avg    : mean distance of Fock space states

---------- 
| suffix |
----------
_exp        : experimental
_sim        : numerical
_fit        : fitted value
_avg        : averaged value
_std        : standard error
_0/60/125   : snapshot times for the Fock state evolution, 0/60/125 (ns)

---------- 
| fields |
----------
Random      : results of random couplings
Optimized   : results of QST-optimized couplings
