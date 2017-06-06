% x = BACKSUB(a,b) computes the solution of an upper triangular
% system a*x = b using back-substitution
%
% inputs
% ------
% a: an n x n upper triangular matrix
% b: an n x 1 column vector
%
% outputs
% -------
% x: the n x 1 solution to the system a*x = b
%
% notes
% -----
% the matrix a need not actually be upper triangular, but only
% the upper triangular part is used
%
% examples
% --------
% x = backsub(triu(magic(3)),ones(3,1))