<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyt9AJc)"><path fill="url(#iZ2fvHe)" class="xdtc11b5a"/></g><path fill="url(#i1y7ppc)" class="raxnhcmlk"/><path fill="url(#iGsVM5d)" class="raxnhcmlk"/><path fill="url(#i45czfg)" class="raxnhcmlk"/><g filter="url(#ii8Rdzb)"><path stroke="url(#iKR14De)" class="jfrsjigpi"/></g><g filter="url(#iIx1O9c)"><path fill="url(#iuLiKbv)" class="hl82k5bic"/><path fill="url(#im0xLUd)" class="hl82k5bic"/><path fill="url(#iYLBlZr)" class="hl82k5bic"/></g><g filter="url(#iwmeZGb)"><path fill="url(#iDJTnoe)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#iurfiGd)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#i72NSNd)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#ifQTbGd)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#iMU41Pd)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#ixokpIc)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#iT9sCTb)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#iT03YWb)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#ilQ3C6b)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#igtSSqr)" clip-rule="evenodd" class="mdidynqjn"/><path fill="url(#iOQ1UZd)" clip-rule="evenodd" class="mdidynqjn"/></g><path fill="url(#iglZ08J)" class="zd5kgpbjv"/><path fill="url(#i8Sxy1t)" class="zd5kgpbjv"/><path fill="url(#i9dL9LX)" class="zd5kgpbjv"/><path fill="url(#iArwFlH)" class="cvet8xwld"/><path fill="url(#iGrcoNm)" class="cvet8xwld"/><path fill="url(#i5QSfLb)" class="cvet8xwld"/><path fill="url(#iCp9RpX)" class="vlhdz3res"/><path fill="url(#i2NwODc)" class="vlhdz3res"/><path fill="url(#itmUtKd)" class="mwwnmeumk"/><g filter="url(#iDlqhSb)"><path fill="url(#ihPnyTm)" class="sago98ywz"/><path fill="url(#iKGJvGb)" class="sago98ywz"/><path fill="url(#ivH1q6c)" class="sago98ywz"/><path fill="url(#iolbLfG)" class="sago98ywz"/></g><g filter="url(#iBvJbjc)"><path fill="url(#iTWsqtC)" class="lt62_rb-d"/><path fill="url(#i8okdGc)" class="lt62_rb-d"/><path fill="url(#i2DT7Yb)" class="lt62_rb-d"/><path fill="url(#ikBoLab)" class="lt62_rb-d"/></g><path fill="url(#iAMBDTo)" class="mq5xlwbof"/><g filter="url(#ieD7Gjb)"><path fill="url(#irQCZpd)" class="nhg8colgr"/><path fill="url(#iKzRnPb)" class="nhg8colgr"/></g><g filter="url(#iMTwabd)"><path fill="url(#iEY8tWJ)" class="i4zjs9bud"/></g><path fill="url(#i2yQzhd)" class="ma3q0mwnw"/><path clip-rule="evenodd" class="cudpxrykb"/><path fill="url(#i6vuYnd)" clip-rule="evenodd" class="ts72ydb_e"/><g filter="url(#iXxUt5c)"><path fill="url(#iF6ORNA)" class="ga6dsnb3i"/><path fill="url(#i9oYwlZ)" class="ga6dsnb3i"/><path fill="url(#iq8pcTb)" class="ga6dsnb3i"/><path fill="url(#ikpgSdc)" class="ga6dsnb3i"/><path fill="url(#iq2WMme)" class="ga6dsnb3i"/><path fill="url(#idlYYPk)" class="ga6dsnb3i"/></g><g filter="url(#id9mHDb)"><path fill="url(#iN9cJzb)" class="fjd5r_wnr"/><path fill="url(#i2qz3HR)" class="fjd5r_wnr"/><path fill="url(#i8Uf8Gm)" class="fjd5r_wnr"/><path fill="url(#idVnRfb)" class="fjd5r_wnr"/><path fill="url(#iU6kqfd)" class="fjd5r_wnr"/></g><path fill="url(#ibXDOpb)" class="l7vtpabbp"/><path fill="url(#iVUoyhc)" class="dq1q10b-i"/><g filter="url(#irGQw2d)"><path stroke="url(#iWC1o1d)" class="fh0246b4a"/></g><g filter="url(#iQSeRxd)"><path stroke="url(#irtyXbb)" class="q0guh3b2p"/></g><g filter="url(#iGjooXd)"><path stroke="url(#ivOMf2M)" class="kpuqaxbmy"/></g><g filter="url(#iekJTie)"><path stroke="url(#iz9OQrh)" class="kmg_vw1zt"/></g><g filter="url(#iFpgcLb)"><path stroke="url(#ixv9dQd)" class="r3r5iules"/></g><g filter="url(#ioR27fc)"><path stroke="url(#io8UFoe)" class="sa_x06b7k"/></g><g filter="url(#iOR0vwd)"><path fill="url(#i74PiLb)" class="mqzdtlbgh"/></g><g filter="url(#iZ6eLvd)"><path fill="url(#iVRoH8c)" class="yq8j73bsn"/><path fill="url(#iGYqYfe)" class="yq8j73bsn"/></g><g filter="url(#ix3qULe)"><path class="sslkx6lar"/><path fill="url(#iVWMDPd)" class="fdhki8bfd"/></g><g filter="url(#iY9kLNe)"><path class="t2a76pbcv"/><path fill="url(#i6152Xb)" class="qa3eakqpi"/></g><g filter="url(#iLVjrzb)"><path fill="url(#imnuTud)" class="a-z1uabgy"/><path fill="url(#iVunXeb)" class="a-z1uabgy"/><path fill="url(#in7v9Mb)" class="a-z1uabgy"/><path fill="url(#ieAnERc)" class="a-z1uabgy"/><path fill="url(#i5roFbc)" class="a-z1uabgy"/><path fill="url(#iWRbzQM)" class="a-z1uabgy"/><path fill="url(#ihouqcd)" class="a-z1uabgy"/></g><path fill="url(#ivV2GRb)" class="a-z1uabgy"/><path fill="url(#iL35Y3d)" class="a-z1uabgy"/><g filter="url(#iduHb0d)"><path class="xsfjkt-bo"/></g><g filter="url(#iICGTKc)"><path class="oyyx94mzq"/><path fill="url(#ike1Aje)" class="pbiao4byi"/><path fill="url(#ihM8uQc)" class="pbiao4byi"/><path fill="url(#i1GZxlc)" class="pbiao4byi"/><path fill="url(#iF6vuFe)" class="pbiao4byi"/></g><path fill="url(#iSdJgne)" class="pbiao4byi"/><path fill="url(#iynqaUc)" class="pbiao4byi"/><path stroke="url(#ix414Vb)" class="h_0wr5btu"/><g filter="url(#i8BUGmd)"><path class="u3ts-zp1p"/></g><g filter="url(#inNQBrd)"><path class="d71sdgbyr"/></g><g filter="url(#iI0Gtdc)"><path class="ph_747i_h"/></g><g filter="url(#iC1zzxc)"><path clip-rule="evenodd" class="p_oex8b2f"/></g><path class="rrnnkfbmu"/><path fill="url(#ijuvlSc)" class="b0izd5b0x"/><path class="iol7y-0lc"/><g filter="url(#iTAQkAI)"><path class="r719xpbki"/><path fill="url(#iKMZ4Lq)" class="ehatmk35g"/></g><g filter="url(#izpLPPc)"><path fill="url(#i0hmhYs)" class="njt0w567t"/></g><path class="d180e0bii"/><path fill="url(#iRpjynb)" class="hilfcplpk"/><path class="aiz7xnb5x"/><g filter="url(#i6v25Bc)"><path fill="url(#i1BcE5b)" class="wgmz_4e_s"/></g><g filter="url(#iI4DVoc)"><ellipse transform="rotate(-27.914 13.556 10.019)" class="cimhjybnd"/><ellipse fill="url(#iZb1OAe)" transform="rotate(-27.914 13.556 10.019)" class="ihc0q-3xc"/></g><g filter="url(#i1sXSeN)"><path class="bbabvdbjh"/></g><g filter="url(#iNKi8cc)"><path class="eu7_rvbly"/></g><g filter="url(#ixi61oc)"><path class="ajm-tp57u"/><path fill="url(#iBHs3Bc)" class="pik0ykblp"/></g><g filter="url(#iunZ8mp)"><path class="dddb9ggzv"/><path fill="url(#iCq3Fed)" class="p-uzttrji"/><path fill="url(#ic10aje)" class="p-uzttrji"/></g><g filter="url(#i72zuXd)"><path stroke="url(#ilHTv7d)" class="f6l7-lbhk"/></g><g filter="url(#iKuePqb)"><path class="bgd3aybzq"/></g><g filter="url(#ig4p6ee)"><path fill="url(#iWM0hob)" class="w0-ozun1u"/><path fill="url(#iDfgX6c)" class="w0-ozun1u"/></g><defs><radialGradient id="iGsVM5d" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.042 6.9)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="i45czfg" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.568 25.48)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iYLBlZr" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.01 4.316)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iurfiGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.708 13.213)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i72NSNd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.892 13.48)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ifQTbGd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.882 8.225)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iMU41Pd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.312 7.71)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ixokpIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.49 2.653)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iT9sCTb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.941 6.89)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iT03YWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.519 9.86)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ilQ3C6b" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.64 8.05)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="igtSSqr" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.027 -3.706)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iOQ1UZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.868 9.824)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iglZ08J" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.013 15.943)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="i8Sxy1t" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.662 20.48)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="i9dL9LX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.724 19.073)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iArwFlH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27 28.23)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="i2NwODc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.464 29.779)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="itmUtKd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 13.2684 15.193 19.082)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iKGJvGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.237 19.44)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="ivH1q6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.9453 -1.33595 .2433 -.17216 19.678 20.45)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iolbLfG" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .92187 -1.72558 .9944 17.988 15.617)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="i8okdGc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.521 20.355)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="ikBoLab" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 .82812 -1.5501 -.64344 14.168 15.883)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iAMBDTo" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.81101 -2.05629 0 16.01 17.23)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="v26cjybkl"/><stop offset="1" class="qlyvrbbxg"/></radialGradient><radialGradient id="irQCZpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.642 23.767)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p4dnf-6nl"/><stop offset="1" class="hi3h5mb3p"/></radialGradient><radialGradient id="iKzRnPb" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.784 23.486)" gradientUnits="userSpaceOnUse"><stop class="rcibyxbcc"/><stop offset="1" class="xcsexhsni"/></radialGradient><radialGradient id="iEY8tWJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.1 24.009)" gradientUnits="userSpaceOnUse"><stop class="esia20bko"/><stop offset="1" class="pycm_h7mj"/></radialGradient><radialGradient id="i9oYwlZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.193 25.36)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iq8pcTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.209 26.642)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="ikpgSdc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.256 27.923)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iq2WMme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.326 29.282)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="i2qz3HR" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.256 25.36)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="i8Uf8Gm" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.193 26.642)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="idVnRfb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.1 27.923)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="iU6kqfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.959 29.282)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="iVRoH8c" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.352 -17.143)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iGYqYfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.08 9.03)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iVWMDPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.401 10.824)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i6152Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.409 10.712)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="imnuTud" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.869 10.174)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iVunXeb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.261 11.536)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="in7v9Mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.63 17.504)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ieAnERc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 16.01 9.957)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="i5roFbc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.331 6.819)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iWRbzQM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.311 9.756)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="ihouqcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.933 9.527)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ivV2GRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.105 11.243)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iL35Y3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.825 4.176)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="ike1Aje" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.794 11.97)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iF6vuFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.555 12.182)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iynqaUc" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.396 8.335)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="ijuvlSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.192 10.115)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKMZ4Lq" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.964 10.199)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRpjynb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.828 10.115)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZb1OAe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.857 -1.499)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBHs3Bc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.403 -4.066)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iCq3Fed" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.084 7.027)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ic10aje" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.22 3.156)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iDfgX6c" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.38 10.158)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><filter id="iyt9AJc" width="27.98" height="21.09" x="2.01" y="3.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="ii8Rdzb" width="27.413" height="20.785" x="2.674" y="3.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".2"/></filter><filter id="iIx1O9c" width="27.91" height="20.96" x="2.01" y="4.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iwmeZGb" width="15.268" height="15.768" x="8.501" y="1.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iDlqhSb" width="2.797" height="14.479" x="18.06" y="15.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iBvJbjc" width="2.797" height="14.486" x="11.153" y="15.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="ieD7Gjb" width="2.1" height="3.39" x="20.953" y="23.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.803922 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iMTwabd" width="2.1" height="3.29" x="8.956" y="23.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iXxUt5c" width="4.793" height="5.391" x="8.956" y="24.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.670588 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="id9mHDb" width="4.793" height="5.591" x="18.46" y="24.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.490196 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.796078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1668" result="effect2_innerShadow_4002_1668"/></filter><filter id="irGQw2d" width="2.222" height=".3" x="18.879" y="25.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="iQSeRxd" width="2.222" height=".3" x="10.866" y="25.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="iGjooXd" width="2.222" height=".3" x="18.879" y="27.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="iekJTie" width="2.222" height=".3" x="10.866" y="27.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="iFpgcLb" width="2.222" height=".3" x="18.879" y="28.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="ioR27fc" width="2.222" height=".3" x="10.866" y="28.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="iOR0vwd" width="3.368" height="3.218" x="9.715" y="9.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iZ6eLvd" width="3.218" height="3.468" x="19.228" y="8.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="ix3qULe" width="3.148" height="3.148" x="19.263" y="9.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".25"/></filter><filter id="iY9kLNe" width="2.948" height="2.948" x="9.869" y="9.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".2"/></filter><filter id="iLVjrzb" width="10.191" height="11.277" x="10.914" y="5.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iduHb0d" width="2.877" height="3.682" x="14.409" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".25"/></filter><filter id="iICGTKc" width="2.377" height="3.182" x="14.821" y="9.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".125"/></filter><filter id="i8BUGmd" width="3.001" height="1.285" x="16.952" y="9.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="inNQBrd" width="3.001" height="1.285" x="12.066" y="9.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iI0Gtdc" width="2.453" height="1.091" x="12.202" y="7.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iC1zzxc" width="2.453" height="1.091" x="17.619" y="7.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/></filter><filter id="iTAQkAI" width=".787" height=".696" x="17.458" y="9.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="izpLPPc" width=".891" height=".913" x="18.298" y="9.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".1"/></filter><filter id="i6v25Bc" width=".986" height="1.04" x="13.855" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".1"/></filter><filter id="iI4DVoc" width=".913" height=".705" x="13.1" y="9.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".05"/></filter><filter id="i1sXSeN" width="2.261" height=".978" x="17.649" y="8.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".1"/></filter><filter id="iNKi8cc" width="2.261" height=".978" x="12.198" y="8.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".1"/></filter><filter id="ixi61oc" width="4.212" height="4.513" x="9.755" y="3.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/><feGaussianBlur result="effect2_foregroundBlur_4002_1668" stdDeviation=".15"/></filter><filter id="iunZ8mp" width="8.767" height="5.782" x="12.839" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/><feGaussianBlur result="effect2_foregroundBlur_4002_1668" stdDeviation=".125"/></filter><filter id="i72zuXd" width="1.145" height="2.31" x="12.819" y="3.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".1"/></filter><filter id="iKuePqb" width="6.427" height="3.372" x="15.428" y="4.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1668" stdDeviation=".375"/></filter><filter id="ig4p6ee" width="10.29" height="4.16" x="10.89" y="8.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1668"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1668" result="effect2_innerShadow_4002_1668"/></filter><linearGradient id="iZ2fvHe" x1="11.824" x2="31.267" y1="4.605" y2="22.84" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="i1y7ppc" x1="30.068" x2="9.131" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iKR14De" x1="13.443" x2="31.256" y1="3.545" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iuLiKbv" x1="-4.901" x2="28.912" y1="25.637" y2="25.637" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="im0xLUd" x1="3.099" x2="3.099" y1="5.199" y2="23.637" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iDJTnoe" x1="20.703" x2="13.898" y1="3.759" y2="16.364" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iGrcoNm" x1="25.179" x2="25.179" y1="30.45" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="i5QSfLb" x1="22.412" x2="23.224" y1="29.262" y2="29.246" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iCp9RpX" x1="7.14" x2="9.534" y1="28.143" y2="28.143" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="ihPnyTm" x1="18.06" x2="20.857" y1="18.37" y2="18.37" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iTWsqtC" x1="13.95" x2="11.153" y1="18.37" y2="18.37" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="i2DT7Yb" x1="12.115" x2="12.678" y1="16.933" y2="17.152" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="i2yQzhd" x1="21.849" x2="17.474" y1="24.793" y2="24.793" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="i6vuYnd" x1="10.32" x2="10.748" y1="23.574" y2="23.574" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iF6ORNA" x1="12.869" x2="8.568" y1="28.012" y2="28.012" gradientUnits="userSpaceOnUse"><stop class="z-u-gxbip"/><stop offset=".716" class="ru_e7vq8a"/></linearGradient><linearGradient id="idlYYPk" x1="11.068" x2="11.068" y1="30.265" y2="29.187" gradientUnits="userSpaceOnUse"><stop class="qgefhk3_g"/><stop offset="1" class="fz4o7ndqt"/></linearGradient><linearGradient id="iN9cJzb" x1="22.474" x2="18.66" y1="27.605" y2="27.605" gradientUnits="userSpaceOnUse"><stop class="tug0m0bta"/><stop offset=".807" class="t9hl_kbdf"/></linearGradient><linearGradient id="ibXDOpb" x1="10.787" x2="21.66" y1="21.949" y2="21.949" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="iVUoyhc" x1="16.407" x2="16.407" y1="21.012" y2="22.183" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iWC1o1d" x1="19.029" x2="20.857" y1="26.113" y2="26.113" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="irtyXbb" x1="12.938" x2="10.74" y1="26.113" y2="26.113" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="ivOMf2M" x1="19.029" x2="20.857" y1="27.379" y2="27.379" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="iz9OQrh" x1="12.938" x2="10.74" y1="27.379" y2="27.379" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="ixv9dQd" x1="19.029" x2="20.857" y1="28.644" y2="28.644" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="io8UFoe" x1="12.938" x2="10.74" y1="28.644" y2="28.644" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="i74PiLb" x1="9.715" x2="12.674" y1="10.799" y2="10.799" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ihM8uQc" x1="15.071" x2="16.01" y1="12.043" y2="12.043" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i1GZxlc" x1="16.01" x2="16.01" y1="12.842" y2="12.232" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iSdJgne" x1="16.088" x2="16.088" y1="12.816" y2="12.676" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="ix414Vb" x1="14.945" x2="15.406" y1="14.252" y2="13.539" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="i0hmhYs" x1="18.97" x2="18.656" y1="10.169" y2="10.362" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1BcE5b" x1="14.572" x2="14.258" y1="10.168" y2="10.362" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilHTv7d" x1="13.118" x2="13.663" y1="4.514" y2="5.787" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iWM0hob" x1="16.085" x2="16.085" y1="9.054" y2="12.836" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-teacher-light" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a-z1uabgy {
  d: path("M10.923 9.45h.012l-.01-.266l-.01-.306c.02-.95.574-1.316.81-1.439l.05-.02q.029-.013.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.a1g7dradx {
  stop-color: var(--svg-color--f2c6bb, #F2C6BB);
  stop-opacity: 0;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.aiz7xnb5x {
  fill: var(--svg-color--000, #000);
  d: path("M14.337 10.53a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ajm-tp57u {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.94 4.723c.566-.599 1.637-.6 2.132-.51l.395 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.989 1.955-2.703 2.145c-.149-1.491.108-2.38.845-3.16");
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b0izd5b0x {
  d: path("M18.194 9.638a.892.892 0 0 1 .86 1.127H17.33a.896.896 0 0 1 .864-1.128");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bbabvdbjh {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.95 8.339c.322-.078 1.124-.04 1.66.344");
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bgd3aybzq {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.416 6.53l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ccj4ms20h {
  stop-color: var(--svg-color--b6736c, #B6736C);
  stop-opacity: 0;
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cimhjybnd {
  cx: 13.556px;
  cy: 10.019px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cudpxrykb {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.414 29.996V21.59H10.32v8.406z");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cvet8xwld {
  d: path("M22.68 29.996V17.751A10.98 10.98 0 0 1 27 26.496v3.5z");
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d180e0bii {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.619 9.366c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.d33s3sdpm {
  stop-color: var(--svg-color--e4af9d, #E4AF9D);
  stop-opacity: 0;
}

.d71sdgbyr {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.868 10.143c-.266-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.27.217-.233.495-.025.6l.556.317c.652-.211 1.373-.24 2.079-.45");
}

.dddb9ggzv {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.407 2.921c-1.133-.25-2.15.88-2.268 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.djg-vfjkd {
  stop-color: var(--svg-color--ffd6c4, #FFD6C4);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dq1q10b-i {
  d: path("M11.153 21.488c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.e_ivvgb2p {
  stop-color: var(--svg-color--b6736c, #B6736C);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.ehatmk35g {
  d: path("M18.128 9.826c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.esia20bko {
  stop-color: var(--svg-color--b88165, #B88165);
}

.eu7_rvbly {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.158 8.339c-.322-.078-1.124-.04-1.66.344");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f6l7-lbhk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.119 4.17c.023.243.234 1.156.544 1.71");
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fdhki8bfd {
  d: path("M20.837 11.786a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fh0246b4a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.03 26.035h1.92");
}

.fjd5r_wnr {
  d: path("M18.66 25.365a.81.81 0 0 0 .303.668a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.84.84 0 0 0-.303.667c.01.421.32.75.685.75h2.935c.426 0 .773-.4.773-.893v-3.605c0-.492-.347-.893-.773-.893h-2.843a.776.776 0 0 0-.777.76");
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fz4o7ndqt {
  stop-color: var(--svg-color--c38792, #C38792);
  stop-opacity: 0;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.ga6dsnb3i {
  d: path("M13.35 25.365a.81.81 0 0 1-.303.668c.178.133.302.37.302.636a.77.77 0 0 1-.302.637a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637c.187.144.302.39.302.667c-.009.421-.32.75-.684.75H9.73c-.427 0-.774-.4-.774-.893v-3.605c0-.492.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_0wr5btu {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.612 13.235a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.247a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.04c-.404.215-.88.338-1.398.338a3 3 0 0 1-1.398-.338Z");
}

.hi3h5mb3p {
  stop-color: var(--svg-color--dda88b, #DDA88B);
}

.hilfcplpk {
  d: path("M13.826 9.638a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hl82k5bic {
  d: path("M29 23.986H3.01V4.996l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i4zjs9bud {
  d: path("M9.956 23.096c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.ihc0q-3xc {
  cx: 13.556px;
  cy: 10.019px;
  rx: 0.39px;
  ry: 0.197px;
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iol7y-0lc {
  fill: var(--svg-color--000, #000);
  d: path("M17.683 10.53a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jfrsjigpi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.224 4.39h26.213a.1.1 0 0 1 .1.1v19.584");
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jtdjejbjn {
  stop-color: var(--svg-color--ffd6c4, #FFD6C4);
  stop-opacity: 0;
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kmg_vw1zt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.938 27.3h-1.922");
}

.kpuqaxbmy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.03 27.3h1.92");
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7vtpabbp {
  d: path("M21.66 22.98v-2.285c0-.389-.36-.7-.81-.7h-8.66c-1.041.001-1.871.73-1.871 1.622c0 .753.61 1.363 1.363 1.363z");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lt62_rb-d {
  d: path("m12.66 16.016l-1.36 2.968c-.09.19.05.41.26.41l.963-.265c.422-.106.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.609z");
}

.ma3q0mwnw {
  d: path("M10.32 21.876v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdidynqjn {
  fill-rule: evenodd;
  d: path("M23.195 12.122c.212-.436.324-.921.324-1.428c0-.467-.096-.905-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.215 3.299v.01a3.24 3.24 0 0 1-.526 1.77l-.002.005a3.3 3.3 0 0 0-.22 3.244c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625H20.3a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.456m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.119 3.96.316l1.135-3.197c-.053-1.244-.956-1.332-1.136-1.332h-3.22A3.86 3.86 0 0 1 13.56 5.92a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mq5xlwbof {
  d: path("M16.01 18.666c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqzdtlbgh {
  d: path("M11.324 12.32a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.mwwnmeumk {
  d: path("M18.06 15.172h-4.11v14.824h4.11z");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n1yz-o_0e {
  stop-color: var(--svg-color--d29c80, #D29C80);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nhg8colgr {
  d: path("M22.053 23.104c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.njt0w567t {
  d: path("M18.989 10.413a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.oyyx94mzq {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.628 10.35l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.p_oex8b2f {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.741 8.476l-.137.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.094-.529c.514-.09.989.001 1.329.11a3.3 3.3 0 0 1 .558.238l.01.006l.003.001z");
}

.p-uzttrji {
  d: path("M15.407 2.921c-1.133-.25-2.15.88-2.268 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.p4dnf-6nl {
  stop-color: var(--svg-color--e9bda6, #E9BDA6);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbiao4byi {
  d: path("m15.628 10.35l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.ph_747i_h {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.612 8.934l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.009-.006a2 2 0 0 1 .148-.077c.099-.047.24-.107.41-.161c.34-.109.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.pik0ykblp {
  d: path("M10.94 4.723c.566-.599 1.637-.6 2.132-.51l.395 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.989 1.955-2.703 2.145c-.149-1.491.108-2.38.845-3.16");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn577vz6t {
  stop-color: var(--svg-color--f2c6bb, #F2C6BB);
}

.pycm_h7mj {
  stop-color: var(--svg-color--cd9a86, #CD9A86);
}

.q0guh3b2p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.938 26.035h-1.922");
}

.qa3eakqpi {
  d: path("M11.343 11.786a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.qgefhk3_g {
  stop-color: var(--svg-color--c38792, #C38792);
}

.qlyvrbbxg {
  stop-color: var(--svg-color--94614b, #94614B);
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r3r5iules {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.03 28.566h1.92");
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.r719xpbki {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.128 9.826c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.raxnhcmlk {
  d: path("M3.01 23.986V4.996H29v18.99z");
}

.rcibyxbcc {
  stop-color: var(--svg-color--fcd2bc, #FCD2BC);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rrnnkfbmu {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.4 9.366c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ru_e7vq8a {
  stop-color: var(--svg-color--d4a093, #D4A093);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sa_x06b7k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.938 28.566h-1.922");
}

.sago98ywz {
  d: path("m19.3 15.992l1.41 2.992c.09.19-.05.41-.26.41l-.964-.265c-.422-.106-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.617z");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sslkx6lar {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.837 11.786a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t2a76pbcv {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.343 11.786a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.t9hl_kbdf {
  stop-color: var(--svg-color--d19890, #D19890);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ts72ydb_e {
  fill-rule: evenodd;
  d: path("M12.414 29.996V21.59H10.32v8.406z");
}

.tug0m0bta {
  stop-color: var(--svg-color--ffd7c3, #FFD7C3);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u3ts-zp1p {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.152 10.143c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.08-.45");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v26cjybkl {
  stop-color: var(--svg-color--b98879, #B98879);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vlhdz3res {
  d: path("M9.3 29.996V17.751a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w0-ozun1u {
  d: path("M20.84 8.648h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wgmz_4e_s {
  d: path("M14.641 10.425c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xcsexhsni {
  stop-color: var(--svg-color--fcd2bc, #FCD2BC);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xdtc11b5a {
  d: path("M29.38 24.986H2.63c-.34 0-.62-.28-.62-.62V4.616c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.xiz-7cblr {
  stop-color: var(--svg-color--e4af9d, #E4AF9D);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xsfjkt-bo {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.617 10.489l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yq8j73bsn {
  d: path("M20.837 12.32a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z-u-gxbip {
  stop-color: var(--svg-color--eab9ad, #EAB9AD);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zd5kgpbjv {
  d: path("M16.01 15.496c-6.07 0-11 4.92-11 11v3.5H27v-3.5c0-6.08-4.92-11-10.99-11");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

</style>
