# programacion_5.8
%NUMERAL P 5.8
%comprobar que el sen 2x=2senx*cosx
clear all
z=linspace(0,2*pi,20);
t=sin(2*z);
plot (z,t,'*')
axis('auto')
title('numeral 5.8')
grid on 
hold on 
c=2*sin(z)
yz=cos(z);
yx=c.*yz;
plot(z,yx,'g')
