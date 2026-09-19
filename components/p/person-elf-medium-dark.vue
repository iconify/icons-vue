<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iK5ifpd)"><path class="rq15x4byi"/><path fill="url(#iQ21Ead)" class="ct5ogkbju"/><path fill="url(#iLMys7d)" class="ct5ogkbju"/></g><path fill="url(#iBt1eBi)" class="ct5ogkbju"/><g filter="url(#iE3DXVc)"><path class="bv-69xbpv"/><path fill="url(#iVGAV7d)" class="pgua_xb8h"/><path fill="url(#iTtCjwc)" class="pgua_xb8h"/></g><path class="txq_035kl"/><path fill="url(#iQMnshd)" class="k98kmhbdx"/><path fill="url(#igkyYLe)" class="k98kmhbdx"/><path fill="url(#ivBqBmb)" class="k98kmhbdx"/><path class="gsenwumws"/><path fill="url(#iZFDHHd)" class="izxcq-l4x"/><path fill="url(#iJXV6Ub)" class="izxcq-l4x"/><path fill="url(#iQgUGRd)" class="izxcq-l4x"/><path class="p3zz4kb9j"/><path fill="url(#iwVhmFd)" class="e7_cr3bza"/><path fill="url(#iPOkLCc)" class="e7_cr3bza"/><path fill="url(#imhPERc)" class="e7_cr3bza"/><path fill="url(#iSVv4Vb)" class="kbs6vktjf"/><path fill="url(#izhbSZc)" class="kbs6vktjf"/><path fill="url(#iveVs0A)" class="kbs6vktjf"/><path fill="url(#i3RFzmd)" class="kbs6vktjf"/><path fill="url(#ijDoaLb)" class="kbs6vktjf"/><path fill="url(#iXxNf8b)" class="kbs6vktjf"/><g filter="url(#i6uVvCA)"><path fill="url(#iZhDCUz)" class="hznm33ftf"/></g><g filter="url(#iqaKuZb)"><path fill="url(#iMi7xEe)" class="oshqjyb1k"/></g><path class="z7q9w9nsq"/><path fill="url(#io2dINc)" class="nmpn19wzd"/><path fill="url(#iItREmH)" class="nmpn19wzd"/><path fill="url(#iCa76SL)" class="nmpn19wzd"/><path fill="url(#i3WYIMe)" class="nmpn19wzd"/><path fill="url(#iEruxub)" class="nmpn19wzd"/><path fill="url(#iIwqxUQ)" class="nmpn19wzd"/><path fill="url(#i5EInCc)" class="nmpn19wzd"/><path fill="url(#icC4Ejd)" class="nmpn19wzd"/><path fill="url(#iz427tZ)" class="v8wnikn7p"/><path fill="url(#iZrwvId)" class="v8wnikn7p"/><path fill="url(#ian4UFS)" class="v8wnikn7p"/><path fill="url(#iN1flod)" class="v8wnikn7p"/><g filter="url(#iVgCWvd)"><path fill="url(#iIf67Ae)" class="drrcjgbmp"/><path fill="url(#iLUfsGe)" class="drrcjgbmp"/></g><path fill="url(#iCcZi4v)" class="s1uyvobna"/><path fill="url(#iDwoSxb)" class="s1uyvobna"/><g filter="url(#ieVvlle)"><path class="f8sdb75ou"/></g><g filter="url(#iU9aNme)"><path class="guqjc7nko"/></g><g filter="url(#ioB5tsb)"><path fill="url(#iX9Z3mr)" class="wj_0ttb5q"/></g><g filter="url(#isPXMPe)"><path fill="url(#iu22WIc)" class="lcblgbkky"/><path fill="url(#ielsSfb)" class="lcblgbkky"/></g><g filter="url(#iIQIJzc)"><path fill="url(#iWcNCNc)" class="ulf-7gbex"/><path fill="url(#iyy32hd)" class="ulf-7gbex"/><path fill="url(#iqB1dBe)" class="ulf-7gbex"/><path fill="url(#ihbfe5d)" class="ulf-7gbex"/><path fill="url(#iCB9uld)" class="ulf-7gbex"/><path fill="url(#ioXUWse)" class="ulf-7gbex"/></g><path fill="url(#idERyfr)" class="ulf-7gbex"/><path fill="url(#iXEefub)" class="guykq4bte"/><path fill="url(#iLVXjmb)" class="guykq4bte"/><path fill="url(#iktQlKd)" class="guykq4bte"/><path fill="url(#ixys8ed)" class="guykq4bte"/><g filter="url(#iABmmTC)"><path fill="url(#izZijic)" class="nbwcfsb-j"/><path fill="url(#iFRRALd)" class="nbwcfsb-j"/></g><g filter="url(#iCIEbce)"><path fill="url(#iYBZyfc)" class="kdvyjshue"/><path fill="url(#i5gg2Me)" class="kdvyjshue"/></g><path fill="url(#iSWw44C)" class="mnbvi-beq"/><path fill="url(#iyRbZUb)" class="mnbvi-beq"/><path fill="url(#iZYe5Mb)" class="mnbvi-beq"/><path fill="url(#ipWMnUD)" class="mnbvi-beq"/><path fill="url(#idbYYpe)" class="mnbvi-beq"/><path fill="url(#iNjnfAc)" class="mnbvi-beq"/><path fill="url(#iD1FxLd)" class="w5vn6kb5o"/><path stroke="url(#iza38nb)" class="c4i1tcc7b"/><path stroke="url(#iPyFqqe)" class="c4i1tcc7b"/><path stroke="url(#ieM3arc)" class="bok5f_uws"/><g filter="url(#iryoCib)"><path class="fwlgbbbyq"/></g><g filter="url(#iancflc)"><path class="bd1l09bfz"/></g><path class="pzder4b0w"/><path fill="url(#iqSTAGb)" class="g1h1v_f7b"/><path fill="url(#iYI6Frw)" class="g1h1v_f7b"/><path fill="url(#if7QhPI)" class="g1h1v_f7b"/><g filter="url(#iVeDF4d)"><path stroke="url(#if7U2zd)" class="f5g35n02h"/></g><path class="xatqm9qgd"/><path class="dde1o5bku"/><path fill="url(#i0O8Yfb)" class="r3bbexlfa"/><path class="q6_fzs7-r"/><g filter="url(#itNjvVc)"><path class="xid210bhr"/><path fill="url(#idv22kN)" class="zhcjv5uud"/></g><g filter="url(#iI47lyR)"><path fill="url(#i5Q6rbc)" class="bbvz2obwe"/></g><path class="rnooggajo"/><path fill="url(#iVXvR2c)" class="i9vyxwwtv"/><path class="xqyb4dz9z"/><g filter="url(#ibCckQe)"><path fill="url(#isi63hb)" class="ql3irgbnp"/></g><g filter="url(#iu2bIDc)"><ellipse transform="rotate(-27.914 13.547 9.778)" class="tp-a8qw8b"/><ellipse fill="url(#iyTjOAc)" transform="rotate(-27.914 13.547 9.778)" class="h6gt32ejx"/></g><g filter="url(#it4mZyc)"><path stroke="url(#iytDscd)" class="jz3fl9fna"/></g><defs><radialGradient id="iQ21Ead" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 11.883)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="cva0eccxo"/><stop offset="1" class="yvvekm_dy"/></radialGradient><radialGradient id="iLMys7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 14.945)" gradientUnits="userSpaceOnUse"><stop class="lp4if9b4k"/><stop offset="1" class="ofalufbug"/><stop offset="1" class="xilj489kn"/></radialGradient><radialGradient id="iBt1eBi" cx="0" cy="0" r="1" gradientTransform="rotate(-65.289 25.201 -8.557)scale(1.9436 3.02274)" gradientUnits="userSpaceOnUse"><stop class="ud4scdcmb"/><stop offset="1" class="ajbrbac6b"/></radialGradient><radialGradient id="iVGAV7d" cx="0" cy="0" r="1" gradientTransform="rotate(-98.799 12.467 4.558)scale(3.20061 3.97853)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="nagianp2z"/><stop offset="1" class="c7ltk09yg"/></radialGradient><radialGradient id="iTtCjwc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39063 .57888 -1.52227 -6.28657 12.111 14.413)" gradientUnits="userSpaceOnUse"><stop class="ok95vkw1c"/><stop offset="1" class="k8vvgib0z"/></radialGradient><radialGradient id="igkyYLe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -11.6596 23.142 20.664)" gradientUnits="userSpaceOnUse"><stop class="t2ybzjp2q"/><stop offset="1" class="wodhbzf-c"/></radialGradient><radialGradient id="ivBqBmb" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.47 5.173)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="i1lv4bpfj"/><stop offset="1" class="mxgskb25j"/></radialGradient><radialGradient id="iZFDHHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 29.916)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="t219k_b_a"/><stop offset="1" class="nrfhyjbig"/></radialGradient><radialGradient id="iJXV6Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.039)" gradientUnits="userSpaceOnUse"><stop class="a3tgwzvkw"/><stop offset="1" class="zjfb-u0iw"/></radialGradient><radialGradient id="iwVhmFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.71323 -.26753 25.58 28.351)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="em6jl46va"/><stop offset="1" class="syfl0-b7z"/></radialGradient><radialGradient id="imhPERc" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.445)" gradientUnits="userSpaceOnUse"><stop class="yy-0gacyg"/><stop offset="1" class="d07-_rbjf"/></radialGradient><radialGradient id="izhbSZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 -2.65624 14.81119 11.32622 15.736 29.758)" gradientUnits="userSpaceOnUse"><stop class="rbi44vm-m"/><stop offset="1" class="qfs6aobhn"/></radialGradient><radialGradient id="iveVs0A" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.243 11.363)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="i3RFzmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.133)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="sb4dv46vs"/><stop offset="1" class="ro5kwtkrd"/></radialGradient><radialGradient id="iZhDCUz" cx="0" cy="0" r="1" gradientTransform="rotate(97.64 -1.617 18.109)scale(3.08805 1.1998)" gradientUnits="userSpaceOnUse"><stop class="xnfwhubut"/><stop offset="1" class="nd_uzdbib"/></radialGradient><radialGradient id="iMi7xEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.508)" gradientUnits="userSpaceOnUse"><stop class="o5xzi4bgi"/><stop offset="1" class="ui8xaew_b"/></radialGradient><radialGradient id="io2dINc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.82031 -7.8263 0 16 16.289)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="wdde7fbgs"/><stop offset="1" class="qt8zeccfx"/></radialGradient><radialGradient id="iItREmH" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 3.875 -2.05328 1.25846 8.83 16.101)" gradientUnits="userSpaceOnUse"><stop class="fg4eg_4fj"/><stop offset="1" class="eul_yij3i"/></radialGradient><radialGradient id="iCa76SL" cx="0" cy="0" r="1" gradientTransform="rotate(57.322 -7.396 18.171)scale(4.91974 4.45192)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="etr4yvr5e"/><stop offset="1" class="b37sysbpy"/></radialGradient><radialGradient id="i3WYIMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.78127 3.28124 -2.8026 1.52144 12.924 15.133)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="r19r51k_n"/><stop offset="1" class="ah36gjjbi"/></radialGradient><radialGradient id="iEruxub" cx="0" cy="0" r="1" gradientTransform="matrix(1.50686 .88968 -2.07086 3.50742 18.196 16.957)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="ol2rfkycm"/><stop offset="1" class="thpmep7jb"/></radialGradient><radialGradient id="iIwqxUQ" cx="0" cy="0" r="1" gradientTransform="rotate(104.647 4.863 15.397)scale(4.14235 9.13048)" gradientUnits="userSpaceOnUse"><stop class="irx6jyb5l"/><stop offset="1" class="jaugt_k_p"/></radialGradient><radialGradient id="i5EInCc" cx="0" cy="0" r="1" gradientTransform="rotate(36.076 -15.3 37.145)scale(.67663 1.97401)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="yx9tb8yxt"/><stop offset="1" class="gy5_zq-5b"/></radialGradient><radialGradient id="icC4Ejd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7235 2.96875 -1.22621 -1.12492 22.585 15.976)" gradientUnits="userSpaceOnUse"><stop class="yapr3et_m"/><stop offset="1" class="ht8m2nb0n"/></radialGradient><radialGradient id="iz427tZ" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -4.22173 2.03479 1.08445 16.142 20.386)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="a6r8tkb8q"/><stop offset="1" class="ek3wc1xpi"/></radialGradient><radialGradient id="iZrwvId" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4375 -2.83801 0 15.98 16.476)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="dadrh123k"/><stop offset="1" class="wkcmii8id"/></radialGradient><radialGradient id="ian4UFS" cx="0" cy="0" r="1" gradientTransform="rotate(42.523 -14.346 24.59)scale(3.58325 2.63576)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="r7a_zqbvk"/><stop offset="1" class="j1d0egomg"/></radialGradient><radialGradient id="iIf67Ae" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -1.59462 3.4012 3.06607 8.861 10.165)" gradientUnits="userSpaceOnUse"><stop class="bv99tyb-i"/><stop offset="1" class="ynhkn8blf"/></radialGradient><radialGradient id="iLUfsGe" cx="0" cy="0" r="1" gradientTransform="rotate(72.147 -.353 10.026)scale(5.60612 3.91608)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="z5yb85rdc"/><stop offset="1" class="ho-6bmb3r"/></radialGradient><radialGradient id="iCcZi4v" cx="0" cy="0" r="1" gradientTransform="rotate(-137.265 7.499 3.484)scale(2.57883 1.75313)" gradientUnits="userSpaceOnUse"><stop class="hdaq7kcyr"/><stop offset="1" class="b9kp-9dwr"/></radialGradient><radialGradient id="iDwoSxb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -1.01563 3.53448 3.04507 9.533 10.788)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="t8no4c6dx"/><stop offset="1" class="kk_u40bcq"/></radialGradient><radialGradient id="iu22WIc" cx="0" cy="0" r="1" gradientTransform="rotate(-54.058 22.006 -15.2)scale(3.85988 2.29361)" gradientUnits="userSpaceOnUse"><stop class="wpgp5neaw"/><stop offset="1" class="hqd78q26u"/></radialGradient><radialGradient id="ielsSfb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11719 -1.04687 3.854 -4.11286 22.707 10.851)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="bua-ombap"/><stop offset="1" class="xf7z99bbu"/></radialGradient><radialGradient id="iWcNCNc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.96875 0 0 -11.4121 19.486 10.982)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="js4o40l_r"/><stop offset=".659" class="rp3b5-b7t"/></radialGradient><radialGradient id="iyy32hd" cx="0" cy="0" r="1" gradientTransform="matrix(-.58044 -1.29687 1.36965 -.61302 13.738 9.554)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="i5qdhu08e"/><stop offset="1" class="efymvq3ng"/></radialGradient><radialGradient id="iqB1dBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.31481 -1.48437 1.67242 -.3547 18.645 9.46)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="v-nhidb-j"/><stop offset="1" class="qzot3l43f"/></radialGradient><radialGradient id="ihbfe5d" cx="0" cy="0" r="1" gradientTransform="rotate(118.989 7.107 8.539)scale(2.64372 1.90605)" gradientUnits="userSpaceOnUse"><stop class="n7gad4bzu"/><stop offset="1" class="ejsfj0d0t"/></radialGradient><radialGradient id="iCB9uld" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 1.34375 -1.786 1.41219 14.52 5.867)" gradientUnits="userSpaceOnUse"><stop class="lh3mafbyp"/><stop offset="1" class="aob-g0oqu"/></radialGradient><radialGradient id="idERyfr" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.30859 -10.2999 0 15.952 9.68)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="afm29ab6e"/><stop offset="1" class="bvm8nhbqg"/></radialGradient><radialGradient id="iXEefub" cx="0" cy="0" r="1" gradientTransform="rotate(120.719 8.287 6.685)scale(5.01638 9.45422)" gradientUnits="userSpaceOnUse"><stop class="wv2v-14ix"/><stop offset="1" class="xthjkccym"/></radialGradient><radialGradient id="iLVXjmb" cx="0" cy="0" r="1" gradientTransform="rotate(75.174 7.7 15.074)scale(3.29728 2.17598)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="v43radc6v"/><stop offset="1" class="sehfhem7y"/><stop offset="1" class="m_na-39vg"/></radialGradient><radialGradient id="iktQlKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 .09375 -.1824 4.6816 9.176 7.023)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="jjmxvob9d"/><stop offset="1" class="mkkd3_bjf"/></radialGradient><radialGradient id="ixys8ed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43752 3.49999 -1.48595 -.61031 11.707 3.554)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="q3pb9hb9i"/><stop offset="1" class="ajacucc-u"/></radialGradient><radialGradient id="iFRRALd" cx="0" cy="0" r="1" gradientTransform="rotate(174.358 7.927 2.626)scale(4.60936 3.17873)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="tpc5qnb0m"/><stop offset="1" class="fnjjkvb8k"/><stop offset="1" class="k8jz4nwoa"/></radialGradient><radialGradient id="iYBZyfc" cx="0" cy="0" r="1" gradientTransform="matrix(3.63293 .1875 -.04917 .95273 18.822 4.664)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="lk3kv4vdi"/><stop offset="1" class="jjsicubdc"/></radialGradient><radialGradient id="i5gg2Me" cx="0" cy="0" r="1" gradientTransform="matrix(1.02498 -1.50045 5.35034 3.65492 18.776 5.43)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="sar3dsa-n"/><stop offset="1" class="mmn-ztcly"/></radialGradient><radialGradient id="ipWMnUD" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.767 5.476)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="idbYYpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iNjnfAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.228 5.164)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="iD1FxLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.978 6.742)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><radialGradient id="if7U2zd" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 -.625 1.875 .98437 14.614 14.133)" gradientUnits="userSpaceOnUse"><stop class="v7a_kmutk"/><stop offset="1" class="wiz5gzb0p"/></radialGradient><radialGradient id="i0O8Yfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6777 .87332 -.95908 -.74426 18.43 9.96)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="idv22kN" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.415 .583)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVXvR2c" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.594 8.425)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="iyTjOAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.531 10.093)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iQMnshd" x1="15.049" x2="15.049" y1="29.917" y2="20.508" gradientUnits="userSpaceOnUse"><stop class="zej61lbmf"/><stop offset="1" class="dsw94cbmu"/></linearGradient><linearGradient id="iQgUGRd" x1="8.912" x2="8.912" y1="29.916" y2="21.101" gradientUnits="userSpaceOnUse"><stop class="ce9e8ebsk"/><stop offset="1" class="u4rwp_bwq"/></linearGradient><linearGradient id="iPOkLCc" x1="24.142" x2="26.611" y1="29.289" y2="21.383" gradientUnits="userSpaceOnUse"><stop offset=".116" class="z5lko3bbf"/><stop offset="1" class="r-ruyz2yf"/></linearGradient><linearGradient id="iSVv4Vb" x1="12.517" x2="22.705" y1="21.258" y2="30.914" gradientUnits="userSpaceOnUse"><stop class="l2u0pibnj"/><stop offset="1" class="nkujmsbyn"/></linearGradient><linearGradient id="ijDoaLb" x1="15.015" x2="15.229" y1="28.651" y2="28.447" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="nstnghbkd"/></linearGradient><linearGradient id="iXxNf8b" x1="19.002" x2="18.65" y1="21.961" y2="22.32" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="iN1flod" x1="17.642" x2="16.895" y1="18.57" y2="18.195" gradientUnits="userSpaceOnUse"><stop class="ql_bnxode"/><stop offset="1" class="k84qsdlfz"/></linearGradient><linearGradient id="iX9Z3mr" x1="21.832" x2="23.715" y1="11.617" y2="8.648" gradientUnits="userSpaceOnUse"><stop offset=".667" class="x0jcpybzt"/><stop offset="1" class="qfss9c9ub"/></linearGradient><linearGradient id="ioXUWse" x1="21.426" x2="19.801" y1="11.367" y2="11.304" gradientUnits="userSpaceOnUse"><stop offset=".267" class="umoaa6lxl"/><stop offset="1" class="uwpc4fbqq"/></linearGradient><linearGradient id="izZijic" x1="12.299" x2="12.97" y1="6.508" y2="3.117" gradientUnits="userSpaceOnUse"><stop class="tlu5wv8ah"/><stop offset="1" class="c5a3cvbzc"/></linearGradient><linearGradient id="iSWw44C" x1="15.58" x2="17.299" y1="5.65" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="iyRbZUb" x1="15.644" x2="15.644" y1="6.307" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="iZYe5Mb" x1="15.969" x2="15.969" y1="4.734" y2="5.32" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient><linearGradient id="iza38nb" x1="13.794" x2="12.142" y1="7.662" y2="8.445" gradientUnits="userSpaceOnUse"><stop class="orvifrbmi"/><stop offset="1" class="jxu-rdb7i"/></linearGradient><linearGradient id="iPyFqqe" x1="13.794" x2="12.142" y1="7.662" y2="8.445" gradientUnits="userSpaceOnUse"><stop class="j9v6w1g-o"/><stop offset="1" class="gknoe_5tx"/></linearGradient><linearGradient id="ieM3arc" x1="18.111" x2="19.762" y1="7.662" y2="8.445" gradientUnits="userSpaceOnUse"><stop class="ntcvcjope"/><stop offset="1" class="ja426ubpr"/></linearGradient><linearGradient id="iqSTAGb" x1="16.848" x2="15.707" y1="11.414" y2="11.633" gradientUnits="userSpaceOnUse"><stop offset=".117" class="yzp1s7u9s"/><stop offset=".685" class="gtx7mebkb"/></linearGradient><linearGradient id="iYI6Frw" x1="15.832" x2="15.832" y1="12.67" y2="12.047" gradientUnits="userSpaceOnUse"><stop offset=".072" class="gbjz6wmhw"/><stop offset="1" class="k4oea-brf"/></linearGradient><linearGradient id="if7QhPI" x1="16" x2="16" y1="9.77" y2="10.414" gradientUnits="userSpaceOnUse"><stop class="jpsqsio8g"/><stop offset="1" class="yntilobtm"/></linearGradient><linearGradient id="i5Q6rbc" x1="18.96" x2="18.646" y1="9.928" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isi63hb" x1="14.562" x2="14.248" y1="9.928" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iytDscd" x1="15.861" x2="14.049" y1="20.476" y2="17.992" gradientUnits="userSpaceOnUse"><stop class="qd6na2-uz"/><stop offset="1" class="syu7jn24l"/></linearGradient><filter id="iK5ifpd" width="7.408" height="7.009" x="17.877" y="11.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.219608 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1366"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.215686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1366" result="effect2_innerShadow_4002_1366"/></filter><filter id="iE3DXVc" width="7.258" height="6.609" x="6.975" y="11.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.215686 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1366"/></filter><filter id="i6uVvCA" width="2.581" height="5.008" x="14.415" y="20.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".25"/></filter><filter id="iqaKuZb" width="1.681" height="4.108" x="15.197" y="20.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1366"/></filter><filter id="iVgCWvd" width="3.872" height="5.121" x="7.884" y="7.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.14902 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1366"/></filter><filter id="ieVvlle" width="3.972" height="5.021" x="20.244" y="7.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1366"/></filter><filter id="iU9aNme" width="3.402" height="2.55" x="20.573" y="7.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".1"/></filter><filter id="ioB5tsb" width="3.267" height="4.113" x="20.648" y="8.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".1"/></filter><filter id="isPXMPe" width="2.552" height="3.266" x="20.8" y="8.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".05"/></filter><filter id="iIQIJzc" width="11.083" height="12.012" x="10.661" y="4.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1366"/></filter><filter id="iABmmTC" width="6.417" height="5.694" x="9.906" y="2.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".125"/></filter><filter id="iCIEbce" width="6.446" height="5.609" x="15.553" y="2.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".125"/></filter><filter id="iryoCib" width="2.169" height=".842" x="17.516" y="7.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".075"/></filter><filter id="iancflc" width="3.187" height="4.4" x="14.104" y="9.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".375"/></filter><filter id="iVeDF4d" width="3.668" height="1.523" x="14.166" y="13.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".075"/></filter><filter id="itNjvVc" width=".787" height=".696" x="17.448" y="9.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".05"/></filter><filter id="iI47lyR" width=".891" height=".913" x="18.287" y="9.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".1"/></filter><filter id="ibCckQe" width=".986" height="1.04" x="13.845" y="9.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".1"/></filter><filter id="iu2bIDc" width=".913" height=".705" x="13.09" y="9.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".05"/></filter><filter id="it4mZyc" width="2.916" height="3.003" x="13.723" y="18.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1366" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-elf-medium-dark" /></template>
<style>
.a3tgwzvkw {
  stop-color: var(--svg-color--82bd6c, #82BD6C);
}

.a6r8tkb8q {
  stop-color: var(--svg-color--7b534b, #7B534B);
}

.afm29ab6e {
  stop-color: var(--svg-color--794659, #794659);
  stop-opacity: 0;
}

.ah36gjjbi {
  stop-color: var(--svg-color--814a40, #814A40);
  stop-opacity: 0;
}

.ajacucc-u {
  stop-color: var(--svg-color--453e3f, #453E3F);
  stop-opacity: 0;
}

.ajbrbac6b {
  stop-color: var(--svg-color--1c1b1a, #1C1B1A);
  stop-opacity: 0;
}

.aob-g0oqu {
  stop-color: var(--svg-color--663c42, #663C42);
  stop-opacity: 0;
}

.b37sysbpy {
  stop-color: var(--svg-color--77473a, #77473A);
  stop-opacity: 0;
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.b9kp-9dwr {
  stop-color: var(--svg-color--634645, #634645);
}

.bbvz2obwe {
  d: path("M18.979 10.172a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.bd1l09bfz {
  fill: var(--svg-color--744449, #744449);
  d: path("m15.447 10.271l-.57 1.838c-.098.379.136.757.467.757h.707c.331 0 .565-.384.468-.757l-.478-1.838c-.102-.407-.487-.407-.594 0");
}

.bok5f_uws {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.46 8.054c-.195-.136-.84-.472-1.719-.375");
}

.bua-ombap {
  stop-color: var(--svg-color--7a524c, #7A524C);
  stop-opacity: 0;
}

.bv-69xbpv {
  fill: var(--svg-color--1a101e, #1A101E);
  d: path("M8.381 12.702c.735-.625 1.279-1.255 1.368-1.594h4.234v3.282l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.024c-.359-1.28.188-2.109 1.297-2.992");
}

.bv99tyb-i {
  stop-color: var(--svg-color--614141, #614141);
}

.bvm8nhbqg {
  stop-color: var(--svg-color--663541, #663541);
}

.c4i1tcc7b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.445 8.054c.195-.136.84-.472 1.718-.375");
}

.c5a3cvbzc {
  stop-color: var(--svg-color--230f20, #230F20);
  stop-opacity: 0;
}

.c7ltk09yg {
  stop-color: var(--svg-color--151f0e, #151F0E);
  stop-opacity: 0;
}

.ce9e8ebsk {
  stop-color: var(--svg-color--4f7e79, #4F7E79);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ct5ogkbju {
  d: path("M23.879 12.898c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.282l3.313 3.328c2.469-.082 3.322-1.085 3.585-2.024c.36-1.28-.187-2.109-1.296-2.992");
}

.cva0eccxo {
  stop-color: var(--svg-color--41393b, #41393B);
}

.d07-_rbjf {
  stop-color: var(--svg-color--67a16e, #67A16E);
  stop-opacity: 0;
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.dadrh123k {
  stop-color: var(--svg-color--613335, #613335);
}

.dde1o5bku {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.39 9.125c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.drrcjgbmp {
  d: path("M8.763 7.754a6.6 6.6 0 0 1 2.473 1.726l.52 3.024c-.356.052-1.371.609-2.633-1.203a10.7 10.7 0 0 1-1.21-2.751c-.152-.536.332-1.001.85-.796");
}

.dsw94cbmu {
  stop-color: var(--svg-color--659d70, #659D70);
  stop-opacity: 0;
}

.e7_cr3bza {
  d: path("M23.088 18.28a10.9 10.9 0 0 1 3.84 8.318v3.319h-3.84z");
}

.efymvq3ng {
  stop-color: var(--svg-color--6f424c, #6F424C);
  stop-opacity: 0;
}

.egerxebfb {
  stop-color: var(--svg-color--694c3f, #694C3F);
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.ek3wc1xpi {
  stop-color: var(--svg-color--694341, #694341);
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.em6jl46va {
  stop-color: var(--svg-color--88c975, #88C975);
}

.etr4yvr5e {
  stop-color: var(--svg-color--77473a, #77473A);
}

.eul_yij3i {
  stop-color: var(--svg-color--9e6c66, #9E6C66);
  stop-opacity: 0;
}

.f5g35n02h {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16 13.687c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.329Z");
}

.f8sdb75ou {
  fill: var(--svg-color--826159, #826159);
  d: path("M23.237 7.754a6.6 6.6 0 0 0-2.474 1.726l-.52 3.024c.357.052 1.372.609 2.634-1.203a10.7 10.7 0 0 0 1.21-2.751c.152-.536-.332-1.001-.85-.796");
}

.fg4eg_4fj {
  stop-color: var(--svg-color--9e6c66, #9E6C66);
}

.fnjjkvb8k {
  stop-color: var(--svg-color--494446, #494446);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwlgbbbyq {
  stroke: var(--svg-color--403635, #403635);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.46 8.054c-.195-.136-.84-.472-1.719-.375");
}

.g1h1v_f7b {
  d: path("m15.618 10.075l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.gbjz6wmhw {
  stop-color: var(--svg-color--7b4653, #7B4653);
}

.gknoe_5tx {
  stop-color: var(--svg-color--0a0a0a, #0A0A0A);
}

.gsenwumws {
  fill: var(--svg-color--74af4b, #74AF4B);
  d: path("M8.912 18.28a10.9 10.9 0 0 0-3.84 8.318v3.319h3.84z");
}

.gtx7mebkb {
  stop-color: var(--svg-color--9b7971, #9B7971);
  stop-opacity: 0;
}

.guqjc7nko {
  stroke: var(--svg-color--92766e, #92766E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.848 9.992c.383-.547 1.589-1.45 2.851-2");
}

.guykq4bte {
  d: path("m10.722 8.104l.042.9a6.7 6.7 0 0 0-.925-.703c-.579-1.153-.547-1.839-.238-2.569c.285-.672.978-1.072 1.422-1.329q.083-.046.153-.089q.116-.069.218-.124c.31-.174.544-.305.996-.856c1.008-1.367 2-1.328 2.72-1.18l.185.039c.335.07.48.1.654.1c.186 0 .315-.027.61-.088l.243-.05c.73-.15 1.738-.188 2.761 1.179c.459.551.696.682 1.012.856q.103.055.222.124l.154.09c.452.256 1.155.656 1.444 1.328c.314.732.347 1.418-.245 2.575c-.413.262-.75.54-1.008.785l.045-.988c.03-.428-.357-1.368-1.269-1.368c-.8 0-1.167.01-1.364.016l-.165.004c-.785 0-1.58-.184-2.126-.984h-.623c-.537.8-1.32.984-2.093.984l-.175-.004a49 49 0 0 0-1.4-.016c-.898 0-1.278.94-1.25 1.368");
}

.gy5_zq-5b {
  stop-color: var(--svg-color--6a3a22, #6A3A22);
  stop-opacity: 0;
}

.h6gt32ejx {
  cx: 13.547px;
  cy: 9.778px;
  rx: 0.39px;
  ry: 0.197px;
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.hdaq7kcyr {
  stop-color: var(--svg-color--5d4241, #5D4241);
}

.ho-6bmb3r {
  stop-color: var(--svg-color--59373e, #59373E);
}

.hqd78q26u {
  stop-color: var(--svg-color--7d5b55, #7D5B55);
}

.ht8m2nb0n {
  stop-color: var(--svg-color--a86b65, #A86B65);
  stop-opacity: 0;
}

.hznm33ftf {
  d: path("M15.706 21.11c.263.22.79.923.79 1.906c0 1.053-.358 1.646-.702 2.06a.115.115 0 0 1-.177 0c-.343-.414-.702-1.007-.702-2.06c0-.983.527-1.686.79-1.907");
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i1lv4bpfj {
  stop-color: var(--svg-color--79b576, #79B576);
}

.i5qdhu08e {
  stop-color: var(--svg-color--6f424c, #6F424C);
}

.i817agb_c {
  stop-color: var(--svg-color--9777b8, #9777B8);
}

.i9vyxwwtv {
  d: path("M13.816 9.397a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.irx6jyb5l {
  stop-color: var(--svg-color--8e5034, #8E5034);
}

.izxcq-l4x {
  d: path("M8.912 18.28a10.9 10.9 0 0 0-3.84 8.318v3.319h3.84z");
}

.j1d0egomg {
  stop-color: var(--svg-color--5b3434, #5B3434);
  stop-opacity: 0;
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.j9v6w1g-o {
  stop-color: var(--svg-color--0a0909, #0A0909);
}

.ja426ubpr {
  stop-color: var(--svg-color--221715, #221715);
}

.jaugt_k_p {
  stop-color: var(--svg-color--8e5034, #8E5034);
  stop-opacity: 0;
}

.jjmxvob9d {
  stop-color: var(--svg-color--403131, #403131);
}

.jjsicubdc {
  stop-color: var(--svg-color--48383d, #48383D);
  stop-opacity: 0;
}

.jpsqsio8g {
  stop-color: var(--svg-color--815850, #815850);
}

.js4o40l_r {
  stop-color: var(--svg-color--966959, #966959);
}

.jxu-rdb7i {
  stop-color: var(--svg-color--221614, #221614);
}

.jz3fl9fna {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.049 18.414L15.61 20.6c.12.125.428.3.703 0");
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k4oea-brf {
  stop-color: var(--svg-color--7b4653, #7B4653);
  stop-opacity: 0;
}

.k84qsdlfz {
  stop-color: var(--svg-color--6b4140, #6B4140);
  stop-opacity: 0;
}

.k8jz4nwoa {
  stop-color: var(--svg-color--45353a, #45353A);
  stop-opacity: 0;
}

.k8vvgib0z {
  stop-color: var(--svg-color--160e18, #160E18);
  stop-opacity: 0;
}

.k98kmhbdx {
  d: path("M5.071 26.599c0-6.036 4.893-10.93 10.929-10.93s10.929 4.894 10.929 10.93v3.318H5.07z");
}

.kbs6vktjf {
  d: path("M16.274 29.917L7.053 20.32a10.95 10.95 0 0 1 5.854-4.207L26.69 29.917z");
}

.kdvyjshue {
  d: path("M21.744 6.625c-.056.825-.357 1.25-.5 1.36c.023-.222-.092-.671-.336-.977a1.01 1.01 0 0 0-.784-.383h-1.247c-.945 0-2.008-.14-2.672-1.086c-.664-.945-.39-1.883 0-2.297a1.174 1.174 0 0 1 1.656-.047c.531.492.961.414 2.094.89s1.86 1.509 1.789 2.54");
}

.kk_u40bcq {
  stop-color: var(--svg-color--674b49, #674B49);
}

.l2u0pibnj {
  stop-color: var(--svg-color--8a5453, #8A5453);
}

.lcblgbkky {
  d: path("M20.955 10.633c.7-.994 1.823-1.7 2.297-1.93c-.407 1.25-1.157 2.75-1.618 2.992a.55.55 0 0 1-.734-.18z");
}

.lh3mafbyp {
  stop-color: var(--svg-color--663c42, #663C42);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk3kv4vdi {
  stop-color: var(--svg-color--48383d, #48383D);
}

.lp4if9b4k {
  stop-color: var(--svg-color--180c11, #180C11);
}

.m_na-39vg {
  stop-color: var(--svg-color--4e4145, #4E4145);
  stop-opacity: 0;
}

.mkkd3_bjf {
  stop-color: var(--svg-color--403131, #403131);
  stop-opacity: 0;
}

.mmn-ztcly {
  stop-color: var(--svg-color--4a3d41, #4A3D41);
}

.mnbvi-beq {
  d: path("M8.85 5.65a.53.53 0 0 1 .529-.53h13.18a.53.53 0 0 1 0 1.06H9.378a.53.53 0 0 1-.53-.53");
}

.mxgskb25j {
  stop-color: var(--svg-color--79b576, #79B576);
  stop-opacity: 0;
}

.n7gad4bzu {
  stop-color: var(--svg-color--886361, #886361);
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.nagianp2z {
  stop-color: var(--svg-color--1a2115, #1A2115);
}

.nbwcfsb-j {
  d: path("M10.16 6.625c.057.825.292 1.336.435 1.445c-.023-.221.132-.67.375-.976c.244-.307.664-.464.883-.47c.076 0 .44-.023 1.196 0c1.484.048 1.937-.148 2.601-1.093s.44-1.875.05-2.289a1.174 1.174 0 0 0-1.657-.047c-.53.492-.96.414-2.093.89s-1.86 1.509-1.79 2.54");
}

.nd_uzdbib {
  stop-color: var(--svg-color--7f4a45, #7F4A45);
}

.nkujmsbyn {
  stop-color: var(--svg-color--bd7e76, #BD7E76);
}

.nmpn19wzd {
  d: path("M12.12 14.601c-.82-.07-1.718.055-2.327 1.11c-.61.96-.793 3.255 1.914 4.5c1.443.663 3.695.898 4.293.898c.633 0 2.85-.235 4.293-.898c2.707-1.245 2.523-3.54 1.914-4.5c-.61-1.055-1.508-1.18-2.328-1.11l-3.88.14z");
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nrfhyjbig {
  stop-color: var(--svg-color--4b8866, #4B8866);
  stop-opacity: 0;
}

.nstnghbkd {
  stop-color: var(--svg-color--975a60, #975A60);
  stop-opacity: 0;
}

.ntcvcjope {
  stop-color: var(--svg-color--211615, #211615);
}

.o5xzi4bgi {
  stop-color: var(--svg-color--fffcc0, #FFFCC0);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofalufbug {
  stop-color: var(--svg-color--120a0c, #120A0C);
  stop-opacity: 0;
}

.ok95vkw1c {
  stop-color: var(--svg-color--160e18, #160E18);
}

.ol2rfkycm {
  stop-color: var(--svg-color--7d422e, #7D422E);
}

.orvifrbmi {
  stop-color: var(--svg-color--221716, #221716);
}

.oshqjyb1k {
  d: path("M15.988 21.07c.264.221.79.924.79 1.907c0 1.052-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.008-.702-2.06c0-.983.528-1.686.791-1.907");
}

.p3zz4kb9j {
  fill: var(--svg-color--93d756, #93D756);
  d: path("M23.088 18.28a10.9 10.9 0 0 1 3.84 8.318v3.319h-3.84z");
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.p8z5r2h1v {
  stop-color: var(--svg-color--8a575a, #8A575A);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
}

.pgua_xb8h {
  d: path("M8.381 12.702c.735-.625 1.279-1.255 1.368-1.594h4.234v3.282l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.024c-.359-1.28.188-2.109 1.297-2.992");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzder4b0w {
  fill: var(--svg-color--7f564f, #7F564F);
  d: path("m15.618 10.075l-.532 1.839c-.109.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.q3pb9hb9i {
  stop-color: var(--svg-color--453e3f, #453E3F);
}

.q6_fzs7-r {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.29c0-.285.227-.512.51-.512a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.qd6na2-uz {
  stop-color: var(--svg-color--b1736a, #B1736A);
}

.qfs6aobhn {
  stop-color: var(--svg-color--a85d71, #A85D71);
  stop-opacity: 0;
}

.qfss9c9ub {
  stop-color: var(--svg-color--8f756d, #8F756D);
  stop-opacity: 0;
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.ql_bnxode {
  stop-color: var(--svg-color--5c3629, #5C3629);
}

.ql3irgbnp {
  d: path("M14.631 10.184c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.qt8zeccfx {
  stop-color: var(--svg-color--92465c, #92465C);
}

.qxnakxbrg {
  stop-color: var(--svg-color--795646, #795646);
}

.qzot3l43f {
  stop-color: var(--svg-color--885553, #885553);
  stop-opacity: 0;
}

.r-ruyz2yf {
  stop-color: var(--svg-color--71ab75, #71AB75);
  stop-opacity: 0;
}

.r19r51k_n {
  stop-color: var(--svg-color--3e190e, #3E190E);
}

.r3bbexlfa {
  d: path("M18.184 9.397a.893.893 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.r7a_zqbvk {
  stop-color: var(--svg-color--3b1917, #3B1917);
}

.rbi44vm-m {
  stop-color: var(--svg-color--a85d71, #A85D71);
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.rnooggajo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.125c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.ro5kwtkrd {
  stop-color: var(--svg-color--824d4f, #824D4F);
  stop-opacity: 0;
}

.rp3b5-b7t {
  stop-color: var(--svg-color--744c4a, #744C4A);
}

.rq15x4byi {
  fill: var(--svg-color--231622, #231622);
  d: path("M23.879 12.898c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.282l3.313 3.328c2.469-.082 3.322-1.085 3.585-2.024c.36-1.28-.187-2.109-1.296-2.992");
}

.s1uyvobna {
  d: path("M11.045 10.633c-.7-.994-1.823-1.7-2.297-1.93c.406 1.25 1.156 2.75 1.617 2.992a.55.55 0 0 0 .735-.18z");
}

.sar3dsa-n {
  stop-color: var(--svg-color--4a3d41, #4A3D41);
  stop-opacity: 0;
}

.sb4dv46vs {
  stop-color: var(--svg-color--512429, #512429);
}

.sehfhem7y {
  stop-color: var(--svg-color--555152, #555152);
  stop-opacity: 0;
}

.syfl0-b7z {
  stop-color: var(--svg-color--88c975, #88C975);
  stop-opacity: 0;
}

.syu7jn24l {
  stop-color: var(--svg-color--b1736a, #B1736A);
  stop-opacity: 0;
}

.t219k_b_a {
  stop-color: var(--svg-color--4b8866, #4B8866);
}

.t2ybzjp2q {
  stop-color: var(--svg-color--99da64, #99DA64);
}

.t8no4c6dx {
  stop-color: var(--svg-color--674b49, #674B49);
  stop-opacity: 0;
}

.thpmep7jb {
  stop-color: var(--svg-color--945740, #945740);
  stop-opacity: 0;
}

.tlu5wv8ah {
  stop-color: var(--svg-color--230f20, #230F20);
}

.tp-3hccxn {
  stop-color: var(--svg-color--9777b8, #9777B8);
  stop-opacity: 0;
}

.tp-a8qw8b {
  cx: 13.547px;
  cy: 9.778px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.tpc5qnb0m {
  stop-color: var(--svg-color--45353a, #45353A);
}

.txq_035kl {
  fill: var(--svg-color--7cb04b, #7CB04B);
  d: path("M5.071 26.599c0-6.036 4.893-10.93 10.929-10.93s10.929 4.894 10.929 10.93v3.318H5.07z");
}

.u4rwp_bwq {
  stop-color: var(--svg-color--639d6c, #639D6C);
  stop-opacity: 0;
}

.ud4scdcmb {
  stop-color: var(--svg-color--182210, #182210);
}

.ui8xaew_b {
  stop-color: var(--svg-color--fee9b4, #FEE9B4);
}

.ulf-7gbex {
  d: path("m10.967 12.976l-.306-5.874c.58-.709 2.468-2.126 5.37-2.126s4.674 1.417 5.213 2.126l-.267 5.887c-.005.446-.219 1.552-.86 2.42c-.8 1.087-2.218 1.579-4.165 1.579s-3.34-.508-4.141-1.594c-.64-.869-.839-1.972-.844-2.418");
}

.umoaa6lxl {
  stop-color: var(--svg-color--987061, #987061);
}

.uwpc4fbqq {
  stop-color: var(--svg-color--9a6c5e, #9A6C5E);
  stop-opacity: 0;
}

.v-nhidb-j {
  stop-color: var(--svg-color--885553, #885553);
}

.v43radc6v {
  stop-color: var(--svg-color--4e4145, #4E4145);
}

.v7a_kmutk {
  stop-color: var(--svg-color--856163, #856163);
}

.v8wnikn7p {
  d: path("m15.719 20.23l-2.871-4.066h6.265L16.25 20.23c-.164.215-.395.2-.531 0");
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.w5vn6kb5o {
  d: path("M15.906 3.622a.103.103 0 0 1 .144 0c.269.257.694.871.694 1.702c0 .974-.346 1.524-.679 1.907a.115.115 0 0 1-.174 0c-.332-.383-.678-.933-.678-1.907c0-.83.425-1.445.693-1.702");
}

.wdde7fbgs {
  stop-color: var(--svg-color--a7606b, #A7606B);
  stop-opacity: 0;
}

.wiz5gzb0p {
  stop-color: var(--svg-color--856163, #856163);
  stop-opacity: 0;
}

.wj_0ttb5q {
  d: path("M20.914 10.767c.849-1.205 2.226-1.99 2.801-2.267c-.25 1.656-1.219 3.117-1.992 3.617c-.424.274-.765-.11-.875-.28z");
}

.wkcmii8id {
  stop-color: var(--svg-color--613335, #613335);
  stop-opacity: 0;
}

.wodhbzf-c {
  stop-color: var(--svg-color--82b84c, #82B84C);
  stop-opacity: 0;
}

.wpgp5neaw {
  stop-color: var(--svg-color--7d5d56, #7D5D56);
}

.wv2v-14ix {
  stop-color: var(--svg-color--423035, #423035);
}

.x0jcpybzt {
  stop-color: var(--svg-color--8f756d, #8F756D);
}

.xatqm9qgd {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16 13.687c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.329");
}

.xf7z99bbu {
  stop-color: var(--svg-color--7a524c, #7A524C);
}

.xid210bhr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.585c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.389-.05");
}

.xilj489kn {
  stop-color: var(--svg-color--180c11, #180C11);
  stop-opacity: 0;
}

.xnfwhubut {
  stop-color: var(--svg-color--6f403b, #6F403B);
}

.xqyb4dz9z {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.29a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.xthjkccym {
  stop-color: var(--svg-color--2d1c28, #2D1C28);
}

.yapr3et_m {
  stop-color: var(--svg-color--ab756a, #AB756A);
}

.ynhkn8blf {
  stop-color: var(--svg-color--593c3c, #593C3C);
}

.yntilobtm {
  stop-color: var(--svg-color--815850, #815850);
  stop-opacity: 0;
}

.yvvekm_dy {
  stop-color: var(--svg-color--41393b, #41393B);
  stop-opacity: 0;
}

.yx9tb8yxt {
  stop-color: var(--svg-color--6a3a22, #6A3A22);
}

.yy-0gacyg {
  stop-color: var(--svg-color--509652, #509652);
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.yzp1s7u9s {
  stop-color: var(--svg-color--9b7971, #9B7971);
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.z5lko3bbf {
  stop-color: var(--svg-color--5a8d7c, #5A8D7C);
}

.z5yb85rdc {
  stop-color: var(--svg-color--694a4c, #694A4C);
  stop-opacity: 0;
}

.z7q9w9nsq {
  fill: var(--svg-color--a16260, #A16260);
  d: path("M12.12 14.601c-.82-.07-1.718.055-2.327 1.11c-.61.96-.793 3.255 1.914 4.5c1.443.663 3.695.898 4.293.898c.633 0 2.85-.235 4.293-.898c2.707-1.245 2.523-3.54 1.914-4.5c-.61-1.055-1.508-1.18-2.328-1.11l-3.88.14z");
}

.zej61lbmf {
  stop-color: var(--svg-color--4d7c7e, #4D7C7E);
}

.zhcjv5uud {
  d: path("M18.118 9.585c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.389-.05");
}

.zjfb-u0iw {
  stop-color: var(--svg-color--74b04f, #74B04F);
  stop-opacity: 0;
}

</style>
