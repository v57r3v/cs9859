java c
EECS   551   Midterm   Exam,   10/12/2022,   6 – 8   pm
1.             If   A, B,   C, D   are   matrices   such   that   the   product   ABCD   is   defined   (conformable), then(ABCD)′   =   D′   C′B′A′   .                                                                                                                                                                                                                                                                                                                                     (2   pts)
True
False2.             If P   is an   orthogonal   projection   matrix, then   ‖(I   −   P)x   ‖2    ≤    ‖x   ‖2                                                                                                                                                             (2   pts)
True
False
3.             If Y   and Z   are   both   unitary   matrices and   B    =   YAZ, then B   and A   have the   same   singular values, assuming the   matrix sizes   match.               (2   pts)
True
False4.             If x    ∈   ℝ3    andy   ∈   ℝ4    are   nonzero vectors, then the   nullity of xy′=2                                                                                           (2   pts)
True
False
5.               Let   b1,   … , bN      be an orthonormal set of vectors   in   FM      and   define   matrix B    =    [b1,   …   , bN   ].Then   ‖Bx‖2      =   ‖x   ‖2    for any x    ∈   FN .                                                                                                                                                                                                                                                                      (2   pts)
True
False6.             For A    =    [3        −4],   ‖Ax‖2    is   maximized for   unit   norm x   when  (2   pts)
True
False
7.             If B   is an orthogonal   projection   matrix   and   B   is   also   an   orthogonal   matrix,   then   B    =   I.            (2   pts)
True
False8.             If A+       =   A′ then A   has orthonormal   columns.                                                                                                                                                                                                                            (2   pts)
True
False9.             If A   is   invertible, then AA+       =   I                                                                                                                                                                                                                                                                                                      (2   pts)
True
False
10.       Let A   be a   Hermitian symmetric   matrix and   Q   be   a   unitary   matrix.   If x   is   a   unit-norm eigenvector of A, then   Q)1x   is a   unit-norm eigenvector of B    =   Q′AQ.                                                (2   pts)
True
False
11.       If x   andy   are two   non-zero vectors   in   ℂN,   then   ‖x   + y‖2       =    ‖x   ‖2    +   ‖y‖2   ,   if y    =   αx   for any   non-zero   α   ∈   ℝ   .                                       (2   pts)
True
False12.         Let   b1,   …   , bN      be a set of   non-zero vectors   in   ℝN      that are   all   pairwise   perpendicular   to   each   other. Then the   matrix B    =   [b1,   … , bN   ]   is an orthogonal   matrix.                                                                                                                   (2   pts)
True
False13.       If A   is an M   × N   matrix with   rank N,   where   M    ≥   N, then A+A    =   I.                                                                                              (2   pts)
True
False14.       If A   is an M   × N   matrix, then   R(A′)   =   R(A′A).                                                                                                                                                                                                                (2   pts)
True
False15.       If A   is an M   × N   matrix, then   R(A)   =   R(AA+   ).                                                                                                                                                                                                                (2   pts)
True
False
16.      The   matrix  for which P2    = I,   has   all   non-zero   eigenvalues.                                                 (2   pts)
True
False17.       Define the   matrix A ∈ R2N×2N such that for   any x ∈ RN   andy ∈ RN   :  
Then the   matrix A is   idempotent.                                                                                                                                                                                                                                                                                        (2   pts)
True
False
18.       If B is a   normal   matrix and z is   any   unit-norm   eigenvector   of   B,   then   there   is   an   SVD   of   B         where z is one of the   left   singular   vectors.                                                                                                                                                                                                                                        (2   pts)
True
False
19.       If A is   an M × N matrix   with   rank   N,   where   M   ≥   N,   then   minx   ⅡAx   —   yⅡ2    =   0.                           (2   pts)
True
False
20.       If   C   =   [A          B] then   minx   ⅡCx   —   yⅡ2    > minz ⅡAz   —   yⅡ2, assuming dimensions   match appropriately.                                                              (2   pts)
True
False21.       If B is   a   200 × 400 matrix with   rank   100,   then:                                                                                                                                                                                                         (2   pts)
a.         dim]R(B)^ =   100
b.         dim]R丄 (B)^   =   100
c.          dim]N(B)^   =   100
d.         dim]N丄 (B)^   =   100
e.       The   number of   distinct   singular values   is   at   least   222.       When  the   unit-norm vector x that   maximizes   ‖Ax‖2   is:                          代 写EECS 551 Midterm ExamR
代做程序编程语言                                         (2   pts)
a.         [1         2]'/√5
b.          [6          4          2]'/√14 
c.            [2         4         6]'/√14 
d.         [2         1]'/√5 
e.         [3          2         1]'/√14 
f.            None of the   above 23.      The value displayed   by the JULIA code          A=ones(2,8);   norm(A,2)   is                                                                                                    (2   pts)
a.         2
b.         4
c.         8
d.         16
e.         32
24.       Let u   and v   be two orthogonal vectors   in   F' . The   number of   non-zero   eigenvalues   of the    matrix uv′   is                                                                                                                                                                                                                                                                                                                                                                                                (2   pts)
a.         0
b.         1
c.            N-1
d.         N
e.         None of the   above25.       For an M   × N   matrix with   rank r,   the   number   of   singular   values   is                                                                                                       (2   pts)
a.         r
b.         M
c.         N
d.         M   +   N
e.         MN
f.          min(N, M)
g.         None of the   above
26.       Let   V   ∈   F'×'    denote   a   unitary   matrix.   For   y   ∈   F', the   most   computationally   efficient
JULIA   code   for   solving   argmin+∈F!   ‖Vx   − y‖!      is:                                                                                                                                                                                        (2   pts)
a.         pinv   (V)   *   y
b.         V   \   y 
c.         V   *   y 
d.         V’   *   y 
e.         Inv(V)   *   y
27.       Let α and β denote the spectral   norms of   matrices A and B,   respectively.   The   spectral norm   of the   matrix  is                                (2   pts)
a. αβ 
b. α + β 
c. √α2 +   β2 
d.         min (α,   β)
e.         max (α,   β)
f.            None of the   above
28.       Let A be an M × N matrix   with   non-zero   rank.   The   orthogonal   complement   of   the   null space of A+    is.                                                                            (2   pts)
a.         R(A)
b.         R(A9)
c.         N(A)
d.         N(A9)
e.         R丄 (A)  
f.            R丄 (A′)  
g.         N丄 (A)  
h.         N丄 (A′) 
29.       Let A be a tall   matrix   having   rank r with SVD given   by  Define   Pr丄 = I − urur ′ and P0(丄)   = I − u0   u0 ′ and   B   = P0(丄)Pr丄 .   Then:                                                                                                    (2   pts)
a.         B is   a   unitary   matrix.
b.         B is   not a   unitary   matrix.
c.          Need   more   information to assess
30.       If B   is an N   × N   idempotent   matrix with   trace{B}   =   K, then rank(B)   is                                                             (2   pts)
a.         0   or   1
b.         K
c.         N   −   K
d.         N
e.         None of the   above
31.      The vectors   {b1, b2, b3   }    form. an orthonormal   basis for   a   subspace S   of   ℝN,   for   N    ≥   5.
Complete the following JULIA function so that given   input vector x    ∈   ℝN,   it   returns the nearest vector   in S.   For full credit, your code   must   use as   few   floating-point   calculations   as   possible.                                                                                        (4   pts)
function neareast   (x, b1, b2,   b3)
return
end
32.       Determine the spectral   norm   of  for   b    ∈   ℝ   .                                                                                                                                                            (4   pts)33.      A simple   linear system takes as   input n   (possibly   complex) scalar   values   and   returns   as         output the sum of those values. Thinking of the   input   as   an n-dimensional   vector,   what   unit   norm   input vector   produces an output value with the   largest   possible   magnitude?       (4   pts)34.       Determine what will   be displayed as   output   by the   following   JULIA   code:                                                                (4   pts)
B   =   [3   0   0   -4];
pinv(B)
35.      Complete the following JULIA function so that   it   returns the   nullity of   a   matrix   argument.            (4   pts)
function nullity   (   A   )
(M,N)=size(A)
return
end36.       Determine the output value displayed   by the following JULIA   code.                                                                                                 (4   pts)
A =   7   *   ones(5,3);
(U,   s, V)      =   svd(A);
B =   U[:,1]   *   s[1]   * V[:,1]’;
Vecnorm   ( A   –   B   )
37.      Complete the following JULIA function so that   it   returns an   orthonormal   basis   (as   a   matrix)   for the span of the four   input vectors   a,   b, c,   d   (assumed   to   be   of   the   same   length).       (4   pts)
function spanbasis   (a,   b,   c,   d)
end38.       Let   U   and V   denote   unitary N   × N   matrices. Complete the   following JULIA   function   so   that
given   input vector y   ∈   ℂN,   it   returns the   linear   least-squares solution
argminx      ‖UVx   − y‖2(2). 
For full credit, your code   must   use as few   floating-point   calculations   as   possible.       (4   pts)
function best   (y, U,   V)
return
end
39.       Determine a simple expression for the   solution   to   the   following   regularized   least-squares
cost   function   for   δ    > 0. x   =   argminxf(x) where   f(x)   = 2/1   ‖Ax   − y‖2(2)   + 2/1   δ   2   ‖Cx‖2(2), where   C   has full column   rank. Your   final expression should   not   have   any   pseudo-inverse   in   it and should   be   in terms of the   original   problem variables: A,   C, y,   δ   .                (8   pts) 



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
