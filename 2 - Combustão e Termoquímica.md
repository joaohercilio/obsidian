### Equação de estado
$$
P = \rho R T
$$
Em que a constante específica do gás  $R$ é relacionada à constante universal $R_u = 8315 \  \mathrm{J/kmol-K}$ e massa molecular $MW$ por

$$R = R_u/MW$$
### Equações calorificas de estado
$$
\begin{aligned}
& u = u(T,v) \\
& h = h(T,v)
\end{aligned}
$$
As equações para diferenciais são expressas por
$$
\begin{align}
	&\mathrm du = \biggr( \frac{\partial u}{\partial T} \biggr)_v \mathrm dT + \biggr( \frac{\partial u}{\partial v} \biggr)_T \mathrm dv \\
	&\mathrm dh = \biggr( \frac{\partial h}{\partial T} \biggr)_P \mathrm dT + \biggr( \frac{\partial h}{\partial P} \biggr)_T \mathrm dP
\end{align}
$$
Das equações acima, reconhecemos 
$$ \begin{align}
& c_{v}\equiv\left({\frac{\partial u}{\partial T}}\right)_{v} \\
& c_{p}\equiv\left({\frac{\partial h}{\partial T}}\right)_{P}
\end{align}$$
Para um gás ideal, os calores específicos geralmente são funções da temperatura.


### Misturas de gases ideais
Duas grandezas importantes utilizadas para caracterizar a composição da mistura são a fração molar e a fração mássica de cada constituinte. 
A fração molar de uma espécie $i$ é definida como
$$\chi_{i}\equiv\frac{N_{i}}{N_{1}+N_{2}+\cdots N_{i}+\cdots}=\frac{N_{i}}{N_{\mathrm{tot}}}$$
em que N1, N2,... são o número de mols de cada espécie.
Similarmente, a fração mássica de uma espécie $i$ é definida como
$$Y_{i}\equiv\frac{m_{i}}{m_{1}+\;m_{2}+\cdots\;m_{i}+\cdots}=\frac{m_{i}}{m_{\mathrm{tot}}}$$
Note que, da definição, obtemos que
$$\begin{align}
& \sum_{i}\chi_{i}=1 \\
& \sum_{i}Y_{i}=1
\end{align}$$
Fração molar e fração mássica podem ser convertidas umas para as outras utilizando os pesos moleculares da espécie de interesse e da mistura
$$\begin{align}
& Y_{i} = \chi_i \frac{MW_i}{MW_{mix}} \\
& \chi_{i} = Y_i \frac{MW_{mix}}{MW_{i}}
\end{align}$$
O peso molecular e facilmente calculado do conhecimento da fração mássica ou da massa molar
$$\begin{align}
& M W_{\mathrm{mix}}=\sum_{i}\chi_{i}M W_{i}\\
& M W_{\mathrm{mix}}={\frac{1}{\sum_{i}(Y_{i}/M W_{i})}}
\end{align}$$
### Primeira Lei da Termodinâmica
$${\dot{Q}}_{c v}-{\dot{W}}_{c v}={\dot{m}}{\biggl[}(h_{o}-h_{i})+{\textstyle{\frac{1}{2}}}\Bigl(\nu_{o}^{2}-\nu_{i}^{2}\Bigr)+g(z_{o}-z_{i}){\biggr]}$$
### Estequiometria
A quantidade estequiométrica de oxidante é apenas a quantidade necessária para queimar uma quantidade de combustível.
Se mais oxidante é fornecido, a mistura é dita pobre
Se menos oxidante é fornecido, a mistura é dita rica (em combustível)
A razão estequiométrica é determinada realizando o balanço atômico. Para um combustível hidrocarboneto, a relação estequiométrica é definida como
$$C_{x}{\mathrm{H}}_{y}+a({\mathrm{O}}_{2}+3.76{\mathrm{N}}_{2})\rightarrow x C{\mathrm{O}}_{2}+(y/2){\mathrm{H}}_{2}\mathrm{O}+3.76a{\mathrm{N}}_{2}$$
em que
$$a=x+y/4$$
A razão estequiométrica ar-combustível é calculada como
$$(A/F)_{\mathrm{stoic}}=\left(\frac{m_{\mathrm{air}}}{m_{\mathrm{fuel}}}\right)_{\mathrm{stoic}}=\frac{4.76a}{1}\frac{M W_{\mathrm{air}}}{M W_{\mathrm{fuel}}}.$$
A razão de equivalência é comumente usada para indicar quantitativamente se uma mistura é rica, pobre ou estequiométrica. Ela é definida como 
$$\Phi={\frac{(A/F)_{\mathrm{stoic}}}{(A/F)}}$$
Com $\Phi > 1$, há excesso de combustível. Com $\Phi < 1$, há excesso de ar. Para a mistura estequiométrica, a razão é unitária.   
### Entalpia padronizada e entalpia de formação
