<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imZHB4c)"><path fill="url(#ieZUZec)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#imoHmCd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iWU5mNc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iqFUw3i)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iTn0Osd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#i5d56qb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iX13Dbc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iswmVtG)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iRFq3zd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ix1Cwid)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iaepPwc)" clip-rule="evenodd" class="bi4mzcbhr"/></g><g filter="url(#i0bvBOl)"><path fill="url(#izEnx5c)" class="glnfjzbdq"/></g><g filter="url(#icNdJQe)"><path fill="url(#i0mW06d)" class="kmbgvqb8x"/><path fill="url(#ihTtdHb)" class="kmbgvqb8x"/></g><g filter="url(#i6a9U7c)"><path class="hlgna5b6q"/><path fill="url(#i6buMHe)" class="pp-_ab0pn"/></g><g filter="url(#i8uUFfe)"><path class="wn2x0_bdo"/><path fill="url(#iBVFNea)" class="o5u1ey-gn"/></g><g filter="url(#iMhaYIb)"><path fill="url(#ihAoTze)" class="rt01_4bix"/><path fill="url(#iRgngSe)" class="rt01_4bix"/><path fill="url(#iwJ2KUZ)" class="rt01_4bix"/><path fill="url(#i36oPGb)" class="rt01_4bix"/><path fill="url(#i1yAQ5c)" class="rt01_4bix"/><path fill="url(#i0zgkec)" class="rt01_4bix"/><path fill="url(#i1Ctzhc)" class="rt01_4bix"/><path fill="url(#iQQng7d)" class="rt01_4bix"/></g><path fill="url(#i3cTupe)" class="rt01_4bix"/><path fill="url(#ib2oesJ)" class="rt01_4bix"/><path fill="url(#iE9gBbb)" class="rt01_4bix"/><g filter="url(#ismwLVd)"><path class="iht8pzb9t"/></g><g filter="url(#ifWqEEK)"><path class="dgdqexbkl"/><path fill="url(#iQr2Bvc)" class="y_9yvacvu"/><path fill="url(#ipBJG7d)" class="y_9yvacvu"/><path fill="url(#ilepr9c)" class="y_9yvacvu"/><path fill="url(#iJLD7oe)" class="y_9yvacvu"/></g><path fill="url(#iNRr31c)" class="y_9yvacvu"/><path fill="url(#i4Bpjwb)" class="y_9yvacvu"/><path stroke="url(#ik1SPse)" class="shjwjd0bz"/><g filter="url(#iPx8aWb)"><path class="koez1lrpe"/></g><g filter="url(#it89G0d)"><path class="vqpuh6tan"/></g><g filter="url(#iaaVfVd)"><path class="g5n94sd4j"/></g><g filter="url(#isa4aKe)"><path clip-rule="evenodd" class="kd-q06bjt"/></g><path class="uf5rerbdy"/><path fill="url(#i8xZvCd)" class="bzggbt_sv"/><path class="jo8lxfo6c"/><g filter="url(#iMA5T7d)"><path class="ctni3bc2i"/><path fill="url(#iUGOHTY)" class="s0kgwh2nk"/></g><g filter="url(#iAhR6nc)"><path fill="url(#itJi0Ic)" class="l41shdc2m"/></g><path class="y03mew75m"/><path fill="url(#i6vcimc)" class="pndew4b9v"/><path class="ohwsnsbac"/><g filter="url(#iDCpGzd)"><path fill="url(#iJg10Sc)" class="xuflm6bwg"/></g><g filter="url(#iwQrl4d)"><ellipse transform="rotate(-27.914 13.547 9.816)" class="pdyfmt2wz"/><ellipse fill="url(#iBTecCL)" transform="rotate(-27.914 13.547 9.816)" class="w2q6f6-7d"/></g><g filter="url(#iSDJnfd)"><path class="ld1syfnot"/></g><g filter="url(#iE5D74E)"><path class="xjqeanj2i"/></g><g filter="url(#igQ3ebe)"><path class="owrtw1pwd"/><path fill="url(#iOZxwjr)" class="ntb7br0fn"/></g><g filter="url(#ir4TWnd)"><path class="k7w-qcb5g"/><path fill="url(#iXXwmeb)" class="ttb9dxbfy"/><path fill="url(#iJqevdb)" class="ttb9dxbfy"/></g><g filter="url(#i0GegsZ)"><path stroke="url(#i9JgFtd)" class="zpok88b9y"/></g><g filter="url(#iaRDuDb)"><path class="xoaj66tiy"/></g><path fill="url(#iqrRyTh)" class="lp-jspbxv"/><path fill="url(#iqexxae)" class="a_spo2cop"/><path fill="url(#i4B8EQi)" class="ax3t7fbst"/><path fill="url(#iXVCujd)" class="ax3t7fbst"/><path class="btt3v60jw"/><path fill="url(#i3XcG7d)" class="td7qnxbmr"/><path fill="url(#i8yy0nd)" class="td7qnxbmr"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><g filter="url(#iw3C5Av)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="imoHmCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.698 13.008)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iWU5mNc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 13.278)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iqFUw3i" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.927 8.121)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iTn0Osd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.364 7.606)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i5d56qb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.212 11.555)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iX13Dbc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.979 6.786)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iswmVtG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.51 9.657)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iRFq3zd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.648 7.948)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ix1Cwid" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.95 -3.804)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iaepPwc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 9.621)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i0mW06d" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 10.948)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ihTtdHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.07 8.827)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i6buMHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 10.621)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iBVFNea" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.7 5.254)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="ihAoTze" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.86 9.971)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iRgngSe" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.847 7.302)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iwJ2KUZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.838 16.479)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i36oPGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 17.023 9.555)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="mg10me7tz"/><stop offset="1" class="u-jqtpaqp"/></radialGradient><radialGradient id="i1yAQ5c" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.336 6.717)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i0zgkec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.553)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="i1Ctzhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 9.324)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iQQng7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.383 7.237)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i3cTupe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.095 11.04)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="ib2oesJ" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.212 2.367)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iE9gBbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 11.964 15.7)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iQr2Bvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.784 11.767)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iJLD7oe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 11.979)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i4Bpjwb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.423 8.232)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="i8xZvCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUGOHTY" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 9.996)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6vcimc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBTecCL" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.752 -1.595)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOZxwjr" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.24 -4.16)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iXXwmeb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.143 6.922)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iJqevdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.21 2.953)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="i4B8EQi" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.747 30.02)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="b2ikzlbxr"/><stop offset="1" class="h9k8kg5xs"/></radialGradient><radialGradient id="iXVCujd" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.994)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="j571032gg"/><stop offset=".927" class="l_zar3b8g"/></radialGradient><radialGradient id="i3XcG7d" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.119)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="d_syq5qya"/><stop offset="1" class="no4na2b-l"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="ieZUZec" x1="20.693" x2="13.888" y1="3.556" y2="16.161" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="izEnx5c" x1="9.756" x2="10.997" y1="10.596" y2="10.596" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="ipBJG7d" x1="15.061" x2="16" y1="11.84" y2="11.84" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ilepr9c" x1="16" x2="16" y1="12.639" y2="12.029" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iNRr31c" x1="16.078" x2="16.078" y1="12.613" y2="12.473" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="ik1SPse" x1="14.936" x2="15.397" y1="14.049" y2="13.336" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="itJi0Ic" x1="18.96" x2="18.646" y1="9.966" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJg10Sc" x1="14.562" x2="14.248" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9JgFtd" x1="13.109" x2="13.653" y1="4.31" y2="5.584" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iqrRyTh" x1="8.815" x2="23.191" y1="15.318" y2="15.318" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqexxae" x1="8.815" x2="23.191" y1="15.288" y2="15.288" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8yy0nd" x1="26.966" x2="27.302" y1="28.838" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="wdf1v2bbt"/><stop offset="1" class="zo7wqerog"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="imZHB4c" width="15.268" height="15.768" x="8.491" y="1.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="i0bvBOl" width="3.368" height="3.218" x="9.705" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="icNdJQe" width="3.218" height="3.468" x="19.218" y="8.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="i6a9U7c" width="3.148" height="3.148" x="19.253" y="8.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".25"/></filter><filter id="i8uUFfe" width="2.648" height="2.648" x="10.009" y="9.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".125"/></filter><filter id="iMhaYIb" width="10.191" height="11.127" x="10.905" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="ismwLVd" width="2.877" height="3.682" x="14.399" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".25"/></filter><filter id="ifWqEEK" width="2.377" height="3.182" x="14.811" y="9.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".125"/></filter><filter id="iPx8aWb" width="3.001" height="1.285" x="16.942" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="it89G0d" width="3.001" height="1.285" x="12.057" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="iaaVfVd" width="2.453" height="1.091" x="12.192" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="isa4aKe" width="2.453" height="1.091" x="17.609" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter><filter id="iMA5T7d" width=".787" height=".696" x="17.448" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".05"/></filter><filter id="iAhR6nc" width=".891" height=".913" x="18.288" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".1"/></filter><filter id="iDCpGzd" width=".986" height="1.04" x="13.845" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".1"/></filter><filter id="iwQrl4d" width=".913" height=".705" x="13.09" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".05"/></filter><filter id="iSDJnfd" width="2.661" height="1.378" x="17.44" y="7.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".2"/></filter><filter id="iE5D74E" width="2.661" height="1.378" x="11.988" y="7.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".2"/></filter><filter id="igQ3ebe" width="4.312" height="4.613" x="9.646" y="3.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/><feGaussianBlur result="effect2_foregroundBlur_3_950" stdDeviation=".2"/></filter><filter id="ir4TWnd" width="8.767" height="5.782" x="12.83" y="2.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/><feGaussianBlur result="effect2_foregroundBlur_3_950" stdDeviation=".125"/></filter><filter id="i0GegsZ" width="1.145" height="2.31" x="12.809" y="3.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".1"/></filter><filter id="iaRDuDb" width="6.927" height="3.872" x="15.168" y="4.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_950" stdDeviation=".5"/></filter><filter id="iw3C5Av" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_950"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-technologist-medium-dark" /></template>
<style>
.a_spo2cop {
  d: path("M16.025 15.289h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.ax3t7fbst {
  d: path("M8.329 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.271.162z");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b2ikzlbxr {
  stop-color: var(--svg-color--86615a, #86615A);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bi4mzcbhr {
  fill-rule: evenodd;
  d: path("M23.185 11.918c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 1.98a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.3v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456A3.213 3.213 0 0 0 11.709 17h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.292 1.275c-.236.122-.79.49-.81 1.439l.01.306z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.btt3v60jw {
  fill: var(--svg-color--936e5f, #936E5F);
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.bzggbt_sv {
  d: path("M18.184 9.435a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.ctni3bc2i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.623c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d_syq5qya {
  stop-color: var(--svg-color--a78075, #A78075);
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dgdqexbkl {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g5n94sd4j {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.602 8.73l-.004.003a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.194");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glnfjzbdq {
  d: path("M11.314 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h9k8kg5xs {
  stop-color: var(--svg-color--714d45, #714D45);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hlgna5b6q {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iht8pzb9t {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.607 10.286l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j571032gg {
  stop-color: var(--svg-color--9b7469, #9B7469);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jo8lxfo6c {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.327c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.k7w-qcb5g {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.397 2.718c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kd-q06bjt {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.731 8.273l-.137.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.kmbgvqb8x {
  d: path("M20.827 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.koez1lrpe {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.142 9.94c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l_zar3b8g {
  stop-color: var(--svg-color--9b7469, #9B7469);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l41shdc2m {
  d: path("M18.979 10.21a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld1syfnot {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.136c.322-.079 1.124-.04 1.66.344");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lp-jspbxv {
  d: path("M16.355 15.289c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.no4na2b-l {
  stop-color: var(--svg-color--a78075, #A78075);
  stop-opacity: 0;
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.ntb7br0fn {
  d: path("M10.93 4.52c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o5u1ey-gn {
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.ohwsnsbac {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.327a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.owrtw1pwd {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.93 4.52c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pdyfmt2wz {
  cx: 13.547px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pndew4b9v {
  d: path("M13.816 9.435a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.pp-_ab0pn {
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
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

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rt01_4bix {
  d: path("M10.913 9.246h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.05-.02q.029-.013.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.685-4.984 4.685c-2.671 0-4.86-1.882-4.983-4.685z");
}

.s0kgwh2nk {
  d: path("M18.118 9.623c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.shjwjd0bz {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.031a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.247a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.04c-.404.215-.88.338-1.398.338a3 3 0 0 1-1.398-.339Z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.td7qnxbmr {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ttb9dxbfy {
  d: path("M15.397 2.718c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.u-jqtpaqp {
  stop-color: var(--svg-color--723b5c, #723B5C);
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uf5rerbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.163c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vqpuh6tan {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.858 9.94c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w2q6f6-7d {
  cx: 13.547px;
  cy: 9.816px;
  rx: 0.39px;
  ry: 0.197px;
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wdf1v2bbt {
  stop-color: var(--svg-color--8c655d, #8C655D);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wn2x0_bdo {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xjqeanj2i {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.136c-.323-.079-1.125-.04-1.661.344");
}

.xoaj66tiy {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.406 6.328l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xuflm6bwg {
  d: path("M14.631 10.222c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.y_9yvacvu {
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.y03mew75m {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.163c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zo7wqerog {
  stop-color: var(--svg-color--8c655d, #8C655D);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zpok88b9y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 3.967c.023.243.234 1.156.544 1.71");
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

</style>
