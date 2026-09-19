<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuZraKi)"><path fill="url(#i5NhU6b)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#igN43Wg)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#iEwVvdd)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#i7tz5BR)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#iAKAeIe)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#iSJQSFc)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#i65SXgw)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#ih2az2b)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#iUBeL4d)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#iZgAYjb)" clip-rule="evenodd" class="k0ftq27pr"/><path fill="url(#iLcj0ig)" clip-rule="evenodd" class="k0ftq27pr"/></g><g filter="url(#iFng2Xi)"><path fill="url(#iVeERpF)" class="ztga85boj"/></g><g filter="url(#iGmeP3c)"><path fill="url(#iwDZEZl)" class="fihi5sbrd"/><path fill="url(#icMk61d)" class="fihi5sbrd"/></g><g filter="url(#iPKayJd)"><path class="w53spefvo"/><path fill="url(#iA3Xz2b)" class="nba52pkju"/></g><g filter="url(#iX2swlb)"><path class="lpru1ur_y"/><path fill="url(#i8ueBHb)" class="t99ab9bbo"/></g><g filter="url(#iUgmSab)"><path fill="url(#iIPnVue)" class="o4-587bue"/><path fill="url(#ikKYUHe)" class="o4-587bue"/><path fill="url(#iq9PTic)" class="o4-587bue"/><path fill="url(#ijrMKxc)" class="o4-587bue"/><path fill="url(#iRnW8rI)" class="o4-587bue"/><path fill="url(#ifcyzde)" class="o4-587bue"/><path fill="url(#ihqYtnb)" class="o4-587bue"/></g><path fill="url(#i1B74Ie)" class="o4-587bue"/><path fill="url(#irTcwtK)" class="o4-587bue"/><g filter="url(#i3oryAb)"><path class="xpxgkfbfk"/></g><g filter="url(#iuRjKwd)"><path class="trf7mu97u"/><path fill="url(#ijzM5be)" class="qh4bo3byg"/><path fill="url(#iRPU98B)" class="qh4bo3byg"/><path fill="url(#iQCq8jd)" class="qh4bo3byg"/><path fill="url(#io5YxQc)" class="qh4bo3byg"/></g><path fill="url(#iRc1HFb)" class="qh4bo3byg"/><path fill="url(#iZWdnGc)" class="qh4bo3byg"/><g filter="url(#iAfPk7d)"><path class="ev0fz2bga"/></g><g filter="url(#irfJFHc)"><path class="jbaymztyz"/></g><path class="yqb6cfbzv"/><path fill="url(#igQRArJ)" class="l-vfnsb9k"/><path class="jfjx_wrrt"/><g filter="url(#iCMkkCe)"><path class="y3cvo6brh"/><path fill="url(#i52yrSc)" class="wh-dn_vac"/></g><g filter="url(#iwll1Vc)"><path fill="url(#iFl5Zne)" class="ywta_-xao"/></g><path class="dg4zghqma"/><path fill="url(#itGlV5U)" class="zfxir_qeb"/><path class="x4h3z4bif"/><g filter="url(#iUqxUpb)"><path fill="url(#ioLjsEb)" class="g8egeob9u"/></g><g filter="url(#ifqDtid)"><ellipse transform="rotate(-27.914 12.907 11.844)" class="fshrsvx3g"/><ellipse fill="url(#i192XBb)" transform="rotate(-27.914 12.907 11.844)" class="kd6oxcchj"/></g><g filter="url(#i0Kbb0d)"><path class="jr61wqbbv"/><path fill="url(#i8yDA8b)" class="cjwcy_bty"/></g><g filter="url(#iTj56Wc)"><path class="gegzgvb0q"/><path fill="url(#it6R9xn)" class="tl6___-jz"/><path fill="url(#i31xdDe)" class="tl6___-jz"/></g><g filter="url(#iHpqjIb)"><path stroke="url(#iqV3yow)" class="y5pwnueug"/></g><g filter="url(#iQsVMEp)"><path class="eyq9_0btb"/></g><g filter="url(#ib1EMre)"><path class="c8k9xxwrt"/></g><g filter="url(#iPY5ZSb)"><path class="uk_6h8bfi"/></g><g filter="url(#iaKQV0c)"><path class="vaue0-bdm"/></g><g filter="url(#ieYCEFd)"><path class="bimj0ebnp"/></g><path class="j8wirvbxr"/><path fill="url(#iJD9oab)" class="y57xohvpz"/><path fill="url(#ioGfCsb)" class="y57xohvpz"/><path fill="url(#iqgXPWH)" class="y57xohvpz"/><path fill="url(#icXzeJb)" class="o-3y3l8ww"/><path fill="url(#i7RDBCe)" class="uza0nib2y"/><path fill="url(#ih3094d)" class="uza0nib2y"/><path fill="url(#igi1Cxd)" class="uza0nib2y"/><path fill="url(#i7tPZsc)" class="uza0nib2y"/><path fill="url(#ivvJGYb)" class="uza0nib2y"/><path fill="url(#iMTmOGc)" class="uza0nib2y"/><path fill="url(#iR3T2Nc)" class="uza0nib2y"/><path fill="url(#iZZ4QUi)" class="spt1f3y0o"/><path fill="url(#inVUPuG)" class="spt1f3y0o"/><path fill="url(#i6AnLvp)" class="c_g0zlbky"/><path fill="url(#iwP8L1c)" class="c_g0zlbky"/><path fill="url(#iomHb0y)" class="c_g0zlbky"/><path fill="url(#icZhhSc)" class="c_g0zlbky"/><path fill="url(#ilUTPVm)" class="x1ls_mb4u"/><path fill="url(#iBxkatc)" class="x1ls_mb4u"/><path fill="url(#i89Wl8b)" class="x1ls_mb4u"/><path fill="url(#iG6Dine)" class="b4ne_pb_z"/><path fill="url(#ihydNqb)" class="b4ne_pb_z"/><path fill="url(#isI4lJb)" class="me1f_zg8u"/><path fill="url(#i6OEnje)" class="me1f_zg8u"/><path fill="url(#iLXbZMd)" class="me1f_zg8u"/><path fill="url(#iijyrsc)" class="me1f_zg8u"/><g filter="url(#in1Bg0c)"><path fill="url(#igdjCDc)" class="hsx7mfqqi"/><path fill="url(#i1UGQyB)" class="hsx7mfqqi"/></g><path fill="url(#i6CdwDe)" class="hsx7mfqqi"/><path fill="url(#imuDvMe)" class="hsx7mfqqi"/><g filter="url(#ikLddNe)"><path fill="url(#i4o7R9b)" class="gglc4fvjf"/></g><defs><radialGradient id="igN43Wg" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .856 14.78)scale(5.79715 7.24182)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iEwVvdd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63425 2.45096 -3.22037 -4.77512 12.07 16.208)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i7tz5BR" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.736 8.943)scale(2.71306 2.08325)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iAKAeIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62694 2.66222 -1.8753 -1.14604 10.464 10.44)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iSJQSFc" cx="0" cy="0" r="1" gradientTransform="matrix(1.73257 3.2961 -4.57548 2.40507 11.563 2.558)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i65SXgw" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.604 7.426)scale(2.56966 3.59106)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ih2az2b" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.903 7.636)scale(2.42042 5.0476)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iUBeL4d" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.37 9.498)scale(3.65879 4.66075)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iZgAYjb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14012 -3.34085 2.64242 -.90177 21.966 8.576)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iLcj0ig" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -106.744 84.74)scale(1.90619 3.08859)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iwDZEZl" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 26.466 -17.318)scale(3.44881 4.21083)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="icMk61d" cx="0" cy="0" r="1" gradientTransform="matrix(1.65861 .92967 -.26283 .46892 22.392 10.598)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iA3Xz2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.90332 -.14158 .11068 1.48787 21.536 12.859)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i8ueBHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52127 0 0 -1.2001 10.2 12.717)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iIPnVue" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.481 8.17)scale(9.02789 12.0837)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="ikKYUHe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.36305 .56867 -.62771 -4.81602 20.099 13.757)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iq9PTic" cx="0" cy="0" r="1" gradientTransform="matrix(1.64804 -4.77511 6.05873 2.09106 13 21.279)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ijrMKxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14583 8.40732 -9.73178 -1.32634 16.682 12.237)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="pvarcdbuv"/><stop offset="1" class="nc5tcfbln"/></radialGradient><radialGradient id="iRnW8rI" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.45 8)scale(8.87112 15.2733)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="ifcyzde" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45063 1.78032 0 18.9 11.512)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="ihqYtnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65452 1.89619 0 13.382 11.224)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="i1B74Ie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62019 0 0 -8.1251 22.423 13.387)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="irTcwtK" cx="0" cy="0" r="1" gradientTransform="rotate(-66.89 21.289 -.642)scale(6.30944 9.67607)" gradientUnits="userSpaceOnUse"><stop class="oiox6aciy"/><stop offset="1" class="toohnxbuu"/></radialGradient><radialGradient id="ijzM5be" cx="0" cy="0" r="1" gradientTransform="matrix(-.57424 -2.57662 .7941 -.17698 16.989 14.303)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="io5YxQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.98249 0 0 -.27468 16.687 14.57)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iZWdnGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7285 1.18668 -1.4262 -2.0774 16.475 13.82)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="igQRArJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02272 -1.62675 0 18.75 11.964)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i52yrSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29235 -.37673 .51867 -.4025 18.463 12.07)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itGlV5U" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02273 -1.62676 0 13.25 11.964)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i192XBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00975 -.6228 .74863 -.01172 12.888 12.24)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8yDA8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5909 -3.4734 1.7769 .81387 8.867 9.29)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="it6R9xn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.66227 5.53574 -9.05064 -4.35267 18.409 2.727)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i31xdDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26514 1.72344 -3.7079 -.57044 16.266 3.193)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iJD9oab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.436)" gradientUnits="userSpaceOnUse"><stop class="gfj1348zm"/><stop offset=".714" class="vqiy7zq_f"/></radialGradient><radialGradient id="ioGfCsb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.47)" gradientUnits="userSpaceOnUse"><stop class="uatqp3rks"/><stop offset="1" class="oln0s8bds"/></radialGradient><radialGradient id="iqgXPWH" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.252)" gradientUnits="userSpaceOnUse"><stop class="leds28lfi"/><stop offset="1" class="x0hvtbbrr"/></radialGradient><radialGradient id="icXzeJb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.274)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="xjoxl1baz"/><stop offset="1" class="xm7oxtb8r"/></radialGradient><radialGradient id="i7RDBCe" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="fupnc-bzv"/><stop offset="1" class="h4nid6imp"/></radialGradient><radialGradient id="ih3094d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2.06252 -1.29855 -3.22666 31 24.235)" gradientUnits="userSpaceOnUse"><stop class="qomb6ec0x"/><stop offset="1" class="ha79_8bui"/></radialGradient><radialGradient id="igi1Cxd" cx="0" cy="0" r="1" gradientTransform="rotate(116.107 1.598 13.3)scale(4.96085 7.77144)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="vxxihotpt"/><stop offset="1" class="amuq4_bzy"/></radialGradient><radialGradient id="ivvJGYb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.5 -3.058)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="fjifp0bsg"/><stop offset="1" class="wn5ytjbyn"/></radialGradient><radialGradient id="iR3T2Nc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3 .29081 .6725 18.155 24.515)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="zlawngbku"/><stop offset="1" class="oc_o5xbok"/></radialGradient><radialGradient id="iZZ4QUi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.843)" gradientUnits="userSpaceOnUse"><stop class="y0cud7bhd"/><stop offset="1" class="irfgqiu-v"/></radialGradient><radialGradient id="i6AnLvp" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.908)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y0d2ypbdf"/><stop offset="1" class="tmdmcl4vt"/></radialGradient><radialGradient id="ilUTPVm" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.494)" gradientUnits="userSpaceOnUse"><stop class="pgf79f9wa"/><stop offset=".615" class="xv-pxlqsu"/></radialGradient><radialGradient id="iG6Dine" cx="0" cy="0" r="1" gradientTransform="rotate(25.705 -37.136 15.8)scale(1.9602 2.66792)" gradientUnits="userSpaceOnUse"><stop class="uiznndb6j"/><stop offset=".697" class="cd2vywbdh"/></radialGradient><radialGradient id="ihydNqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 .26697 -.4987 -1.61843 4.819 17.232)" gradientUnits="userSpaceOnUse"><stop class="djew4vbxv"/><stop offset="1" class="qgkg7gbyq"/></radialGradient><radialGradient id="isI4lJb" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.296 6.369)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="k06as4b5x"/><stop offset="1" class="xfmd1de7c"/></radialGradient><radialGradient id="i6OEnje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.162 13.251)" gradientUnits="userSpaceOnUse"><stop class="z-bv-oxvq"/><stop offset="1" class="ba2ysf3ct"/></radialGradient><radialGradient id="iijyrsc" cx="0" cy="0" r="1" gradientTransform="matrix(2.96386 -2.56198 2.74355 3.17391 24.182 21.102)" gradientUnits="userSpaceOnUse"><stop class="jrj308b2k"/><stop offset="1" class="sbo-zor_o"/></radialGradient><radialGradient id="i1UGQyB" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.313)" gradientUnits="userSpaceOnUse"><stop class="ypu5blbsz"/><stop offset="1" class="evh185ecb"/></radialGradient><radialGradient id="i6CdwDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.4554 -4.55404 4.5889 -.4589 7.38 23.28)" gradientUnits="userSpaceOnUse"><stop class="pcgaf6bek"/><stop offset="1" class="d9c9r_gmq"/></radialGradient><radialGradient id="imuDvMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03449 -.40327 1.31923 3.38417 4.578 18.232)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="th3on_b5q"/><stop offset="1" class="jztexxbfv"/></radialGradient><filter id="iuZraKi" width="19.181" height="19.681" x="6.534" y="1.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="iFng2Xi" width="4.207" height="4.057" x="8.065" y="10.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="iGmeP3c" width="4.057" height="4.307" x="20.057" y="10.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="iPKayJd" width="3.708" height="3.708" x="20.231" y="10.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".25"/></filter><filter id="iX2swlb" width="3.508" height="3.508" x="8.364" y="10.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".2"/></filter><filter id="iUgmSab" width="12.846" height="14.111" x="9.577" y="6.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="i3oryAb" width="3.366" height="4.381" x="14.112" y="11.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".25"/></filter><filter id="iuRjKwd" width="2.866" height="3.881" x="14.567" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".125"/></filter><filter id="iAfPk7d" width="3.731" height="1.62" x="17.24" y="10.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="irfJFHc" width="3.731" height="1.62" x="11.029" y="10.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="iCMkkCe" width=".94" height=".826" x="17.851" y="11.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".05"/></filter><filter id="iwll1Vc" width="1.019" height="1.047" x="18.936" y="11.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".1"/></filter><filter id="iUqxUpb" width="1.139" height="1.207" x="13.335" y="11.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".1"/></filter><filter id="ifqDtid" width="1.099" height=".836" x="12.358" y="11.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".05"/></filter><filter id="i0Kbb0d" width="5.201" height="5.581" x="8.094" y="4.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/><feGaussianBlur result="effect2_foregroundBlur_3987_24807" stdDeviation=".2"/></filter><filter id="iTj56Wc" width="10.909" height="7.158" x="12.082" y="2.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/><feGaussianBlur result="effect2_foregroundBlur_3987_24807" stdDeviation=".125"/></filter><filter id="iHpqjIb" width="1.287" height="2.755" x="12.055" y="4.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".1"/></filter><filter id="iQsVMEp" width="9.711" height="5.86" x="14.462" y="4.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".875"/></filter><filter id="ib1EMre" width="2.984" height="1.44" x="11.376" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0823529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="iPY5ZSb" width="2.984" height="1.44" x="17.939" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0823529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="iaKQV0c" width="2.617" height="1.134" x="11.536" y="9.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".1"/></filter><filter id="ieYCEFd" width="2.781" height="1.17" x="17.946" y="9.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".1"/></filter><filter id="in1Bg0c" width="7.3" height="8.016" x="2" y="12.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.627451 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24807"/></filter><filter id="ikLddNe" width="5.538" height="5.423" x="24.197" y="13.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24807" stdDeviation=".2"/></filter><linearGradient id="i5NhU6b" x1="21.916" x2="13.338" y1="3.953" y2="19.842" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iVeERpF" x1="8.065" x2="11.796" y1="12.827" y2="12.827" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iRPU98B" x1="14.817" x2="16" y1="14.395" y2="14.395" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iQCq8jd" x1="16" x2="16" y1="15.402" y2="14.633" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iRc1HFb" x1="16.099" x2="16.099" y1="15.369" y2="15.194" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="iFl5Zne" x1="19.731" x2="19.336" y1="12.032" y2="12.276" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ioLjsEb" x1="14.187" x2="13.791" y1="12.032" y2="12.276" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqV3yow" x1="12.355" x2="13.042" y1="4.904" y2="6.509" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="i7tPZsc" x1="9.156" x2="10.486" y1="18.533" y2="19.157" gradientUnits="userSpaceOnUse"><stop class="x0-05wb5o"/><stop offset="1" class="b_wdx7bxu"/></linearGradient><linearGradient id="iMTmOGc" x1="17.482" x2="17.906" y1="26.739" y2="25.783" gradientUnits="userSpaceOnUse"><stop class="jbvrfolcv"/><stop offset=".46" class="byl3sfbil"/></linearGradient><linearGradient id="inVUPuG" x1="24.108" x2="23.968" y1="18.344" y2="18.41" gradientUnits="userSpaceOnUse"><stop class="zb0hqnb-l"/><stop offset="1" class="sqzs4ozft"/></linearGradient><linearGradient id="iwP8L1c" x1="14.945" x2="14.231" y1="27.177" y2="25.57" gradientUnits="userSpaceOnUse"><stop class="na3bqccxs"/><stop offset="1" class="tndlebqua"/></linearGradient><linearGradient id="iomHb0y" x1="22.968" x2="21.812" y1="18.703" y2="19.266" gradientUnits="userSpaceOnUse"><stop class="fp2c12bya"/><stop offset="1" class="xyqac8gqa"/></linearGradient><linearGradient id="icZhhSc" x1="3.231" x2="6.517" y1="28.32" y2="26.713" gradientUnits="userSpaceOnUse"><stop class="m_3r9vbdq"/><stop offset="1" class="iioqnhb4d"/></linearGradient><linearGradient id="iBxkatc" x1="27.52" x2="26.84" y1="19.689" y2="18.127" gradientUnits="userSpaceOnUse"><stop class="nrxa3zsae"/><stop offset="1" class="bnl8ulbdv"/></linearGradient><linearGradient id="i89Wl8b" x1="26.75" x2="27.494" y1="17.424" y2="18.183" gradientUnits="userSpaceOnUse"><stop offset=".353" class="jxqufcbzg"/><stop offset="1" class="o24g7qb2o"/></linearGradient><linearGradient id="iLXbZMd" x1="25.489" x2="25.997" y1="14.315" y2="15.215" gradientUnits="userSpaceOnUse"><stop class="odlbd947j"/><stop offset="1" class="izl0csmmw"/><stop offset="1" class="yjwkbfbeo"/></linearGradient><linearGradient id="igdjCDc" x1="8" x2="5.5" y1="15.783" y2="19.549" gradientUnits="userSpaceOnUse"><stop offset=".206" class="h8_gk412t"/><stop offset="1" class="wrh5y-bmk"/></linearGradient><linearGradient id="i4o7R9b" x1="29.217" x2="24.074" y1="14.879" y2="17.747" gradientUnits="userSpaceOnUse"><stop class="wvl4ponzh"/><stop offset="1" class="sa15ql7ok"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-no-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.amuq4_bzy {
  stop-color: var(--svg-color--9771d7, #9771D7);
  stop-opacity: 0;
}

.b_wdx7bxu {
  stop-color: var(--svg-color--62429a, #62429A);
  stop-opacity: 0;
}

.b4ne_pb_z {
  d: path("M7.246 19.806a.885.885 0 0 0-.351-1.203l-2.553-1.397a.899.899 0 1 0-.855 1.58l2.565 1.374a.885.885 0 0 0 1.194-.354");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.ba2ysf3ct {
  stop-color: var(--svg-color--ffd7c0, #FFD7C0);
  stop-opacity: 0;
}

.bimj0ebnp {
  stroke: var(--svg-color--2f2e2f, #2F2E2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.428 10.073l-2.182-.57");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bnl8ulbdv {
  stop-color: var(--svg-color--d99793, #D99793);
  stop-opacity: 0;
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.byl3sfbil {
  stop-color: var(--svg-color--684c9e, #684C9E);
  stop-opacity: 0;
}

.c_g0zlbky {
  d: path("M20.44 16.132L5.033 23.304a3.53 3.53 0 0 0-1.7 4.691A3.516 3.516 0 0 0 8.011 29.7l15.407-7.183c.503-.232.724-.837.483-1.341l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.c8k9xxwrt {
  fill: var(--svg-color--0b0a09, #0B0A09);
  d: path("M11.388 10.217a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 0 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cd2vywbdh {
  stop-color: var(--svg-color--cd857c, #CD857C);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cjwcy_bty {
  d: path("M9.61 5.168c.713-.755 2.063-.756 2.686-.643l.499 1.626c-.319-.049-.603.064-.842.296c-.565 1.59-2.508 2.465-3.408 2.705c-.187-1.88.137-3 1.065-3.984");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d9c9r_gmq {
  stop-color: var(--svg-color--c87670, #C87670);
  stop-opacity: 0;
}

.dg4zghqma {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.986 11.02a1.76 1.76 0 0 0-1.708 1.335c-.056.22.113.43.338.43h2.812a.29.29 0 0 0 .286-.343a1.766 1.766 0 0 0-1.728-1.421");
}

.djew4vbxv {
  stop-color: var(--svg-color--d28c70, #D28C70);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.ev0fz2bga {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.44 12c.334-.589.843-1.053 1.938-1.053c.479 0 .941.132 1.352.464c.339.274.293.625.031.756l-.7.4c-.823-.266-1.731-.302-2.621-.567");
}

.evh185ecb {
  stop-color: var(--svg-color--fbc7b5, #FBC7B5);
  stop-opacity: 0;
}

.eyq9_0btb {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m19.033 7.447l-1.797.33a.867.867 0 1 1-.157-1.72h2.95c1.746 0 2.323 1.758 2.394 2.36a3.97 3.97 0 0 0-3.39-.97");
}

.fihi5sbrd {
  d: path("M22.085 14.746a2.028 2.028 0 1 0 0-4.057a2.028 2.028 0 0 0 0 4.057");
}

.fjifp0bsg {
  stop-color: var(--svg-color--745b8c, #745B8C);
}

.fp2c12bya {
  stop-color: var(--svg-color--a680df, #A680DF);
}

.fshrsvx3g {
  cx: 12.907px;
  cy: 11.844px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.249px;
}

.ft5dv1b6b {
  fill: none;
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
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

.g8egeob9u {
  d: path("M14.275 12.356c0-.364-.296-.606-.376-.68l-.363.352l.223.456z");
}

.gegzgvb0q {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.24 2.896c-1.428-.315-2.71 1.11-2.858 1.638c1.326 4.469 4.68 4.224 7.992 3.856c1.982-.22 2.197.683 2.366 1.12c0-4.958-4.215-5.888-7.464-6.606z");
}

.gfj1348zm {
  stop-color: var(--svg-color--6547af, #6547AF);
}

.gglc4fvjf {
  d: path("M26.691 15.656c.527-.846 1.795-1.665 2.462-1.988a.13.13 0 0 1 .153.035a.132.132 0 0 1-.034.196c-2.06 1.272-1.875 1.784-2.645 3.097c-.354.604-1.176 1.112-1.556 1.283l-.474-.898c.53-.281 1.463-.712 2.094-1.725");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h4nid6imp {
  stop-color: var(--svg-color--593b97, #593B97);
}

.h8_gk412t {
  stop-color: var(--svg-color--ffd5b9, #FFD5B9);
}

.ha79_8bui {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
  stop-opacity: 0;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hsx7mfqqi {
  d: path("m9 16.103l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iioqnhb4d {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.irfgqiu-v {
  stop-color: var(--svg-color--58448e, #58448E);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.izl0csmmw {
  stop-color: var(--svg-color--c6916f, #C6916F);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j8wirvbxr {
  fill: var(--svg-color--87004e, #87004E);
  d: path("M15.989 19.484c.791 0 1.433-.689 1.433-1.538s-.642-1.538-1.433-1.538s-1.433.689-1.433 1.538s.642 1.538 1.433 1.538");
}

.jbaymztyz {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.56 12c-.334-.589-.843-1.053-1.937-1.053c-.48 0-.942.132-1.353.464c-.339.274-.293.625-.03.756l.7.4c.822-.266 1.73-.302 2.62-.567");
}

.jbvrfolcv {
  stop-color: var(--svg-color--684c9e, #684C9E);
}

.jfjx_wrrt {
  fill: var(--svg-color--000, #000);
  d: path("M18.109 12.488c0-.358.286-.644.644-.644a.642.642 0 0 1 .573.94h-1.14a.6.6 0 0 1-.077-.296");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jr61wqbbv {
  fill: var(--svg-color--232121, #232121);
  d: path("M9.61 5.168c.713-.755 2.063-.756 2.686-.643l.499 1.626c-.319-.049-.603.064-.842.296c-.565 1.59-2.508 2.465-3.408 2.705c-.187-1.88.137-3 1.065-3.984");
}

.jrj308b2k {
  stop-color: var(--svg-color--d98a84, #D98A84);
}

.jxqufcbzg {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
}

.jztexxbfv {
  stop-color: var(--svg-color--e2a594, #E2A594);
  stop-opacity: 0;
}

.k06as4b5x {
  stop-color: var(--svg-color--fccbb6, #FCCBB6);
}

.k0ftq27pr {
  fill-rule: evenodd;
  d: path("M25.058 14.494c.267-.548.408-1.16.408-1.799c0-.589-.122-1.141-.339-1.645h.007a4 4 0 0 0-.355-.647l-.002-.004a4.1 4.1 0 0 1-.664-2.232v-.013a4.16 4.16 0 0 0-4.158-4.159a.68.68 0 0 1-.574-.293A4.17 4.17 0 0 0 16 1.967c-1.39 0-2.628.689-3.38 1.735a.71.71 0 0 1-.575.293l-.107.001a4.16 4.16 0 0 0-4.052 4.158v.013c0 .79-.23 1.569-.663 2.232l-.003.005a4.16 4.16 0 0 0-.277 4.09a.65.65 0 0 1 0 .574a4.1 4.1 0 0 0-.409 1.774a4.05 4.05 0 0 0 4.057 4.056h10.818a4.05 4.05 0 0 0 4.057-4.056c0-.638-.153-1.238-.409-1.774a.65.65 0 0 1 0-.574M9.603 11.125h-.016l1.511 2.97c.156 3.533 1.534 0 4.902 0c3.367 0 4.836 3.932 4.991.4l1.432-4.031c-.067-1.57-1.205-1.68-1.432-1.68h-4.059a4.87 4.87 0 0 1-4.02-2.109a.332.332 0 0 0-.582.065l-.103.244a2.9 2.9 0 0 1-1.564 1.582l-.065.026c-.297.154-.995.617-1.021 1.813l.013.386z");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kd6oxcchj {
  cx: 12.907px;
  cy: 11.844px;
  rx: 0.491px;
  ry: 0.249px;
}

.l-vfnsb9k {
  d: path("M18.753 11.363a1.125 1.125 0 0 1 1.084 1.422h-2.173a1.13 1.13 0 0 1 1.09-1.422");
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

.leds28lfi {
  stop-color: var(--svg-color--785e96, #785E96);
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

.lpru1ur_y {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M10.118 14.071a1.354 1.354 0 1 0 0-2.708a1.354 1.354 0 0 0 0 2.708");
}

.m_3r9vbdq {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0.939;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me1f_zg8u {
  d: path("m23 16.103l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.na3bqccxs {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
}

.nba52pkju {
  d: path("M22.085 14.071a1.354 1.354 0 1 0 0-2.708a1.354 1.354 0 0 0 0 2.708");
}

.nc5tcfbln {
  stop-color: var(--svg-color--b47896, #B47896);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nrxa3zsae {
  stop-color: var(--svg-color--d99793, #D99793);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o-3y3l8ww {
  d: path("m6.81 20.603l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.o24g7qb2o {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
  stop-opacity: 0;
}

.o4-587bue {
  d: path("M9.587 11.125h.016l-.013-.334l-.013-.386c.026-1.196.724-1.659 1.021-1.813l.065-.026q.034-.016.064-.026a2.9 2.9 0 0 0 1.5-1.556l.103-.244a.332.332 0 0 1 .582-.065a4.87 4.87 0 0 0 4.02 2.11h4.06c.226 0 1.363.11 1.431 1.679l-.15 3.874c-.155 3.533-2.914 5.905-6.281 5.905c-3.368 0-6.127-2.372-6.282-5.905z");
}

.oc_o5xbok {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odlbd947j {
  stop-color: var(--svg-color--d6af98, #D6AF98);
}

.oiox6aciy {
  stop-color: var(--svg-color--b9847d, #B9847D);
}

.oln0s8bds {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pcgaf6bek {
  stop-color: var(--svg-color--c87670, #C87670);
}

.pgf79f9wa {
  stop-color: var(--svg-color--ffd2be, #FFD2BE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvarcdbuv {
  stop-color: var(--svg-color--b47896, #B47896);
  stop-opacity: 0;
}

.qgkg7gbyq {
  stop-color: var(--svg-color--d28c70, #D28C70);
  stop-opacity: 0;
}

.qh4bo3byg {
  d: path("m15.518 12.262l-.67 2.143a.68.68 0 0 0 .656.881h.992a.682.682 0 0 0 .656-.881l-.67-2.143c-.144-.475-.814-.475-.964 0");
}

.qomb6ec0x {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
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

.sa15ql7ok {
  stop-color: var(--svg-color--ffd0bc, #FFD0BC);
  stop-opacity: 0;
}

.sbo-zor_o {
  stop-color: var(--svg-color--d98a84, #D98A84);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.spt1f3y0o {
  d: path("m25.19 20.603l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.sqzs4ozft {
  stop-color: var(--svg-color--8071aa, #8071AA);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t99ab9bbo {
  d: path("M10.118 14.071a1.354 1.354 0 1 0 0-2.708a1.354 1.354 0 0 0 0 2.708");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.th3on_b5q {
  stop-color: var(--svg-color--e2a594, #E2A594);
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tl6___-jz {
  d: path("M15.24 2.896c-1.428-.315-2.71 1.11-2.858 1.638c1.326 4.469 4.68 4.224 7.992 3.856c1.982-.22 2.197.683 2.366 1.12c0-4.958-4.215-5.888-7.464-6.606z");
}

.tmdmcl4vt {
  stop-color: var(--svg-color--69569a, #69569A);
}

.tndlebqua {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
  stop-opacity: 0;
}

.toohnxbuu {
  stop-color: var(--svg-color--b9847d, #B9847D);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.trf7mu97u {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.518 12.262l-.67 2.143a.68.68 0 0 0 .656.881h.992a.682.682 0 0 0 .656-.881l-.67-2.143c-.144-.475-.814-.475-.964 0");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uatqp3rks {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
}

.uiznndb6j {
  stop-color: var(--svg-color--e8ad95, #E8AD95);
}

.uk_6h8bfi {
  fill: var(--svg-color--0b0a09, #0B0A09);
  d: path("M20.711 10.217a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 0 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.uza0nib2y {
  d: path("m11.56 16.132l15.407 7.177a3.53 3.53 0 0 1 1.7 4.688a3.52 3.52 0 0 1-4.679 1.703L8.581 22.513a1 1 0 0 1-.483-1.341l2.123-4.567a1.004 1.004 0 0 1 1.339-.473");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vaue0-bdm {
  stroke: var(--svg-color--2f2e2f, #2F2E2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 10.037l2.017-.534");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vqiy7zq_f {
  stop-color: var(--svg-color--53329c, #53329C);
}

.vxxihotpt {
  stop-color: var(--svg-color--9771d7, #9771D7);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w53spefvo {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M22.085 14.071a1.354 1.354 0 1 0 0-2.708a1.354 1.354 0 0 0 0 2.708");
}

.wh-dn_vac {
  d: path("M18.67 11.6c.08.108-.087.239-.278.381c-.19.143-.331.243-.411.136c-.08-.108.009-.31.2-.452c.19-.143.41-.171.49-.064");
}

.wn5ytjbyn {
  stop-color: var(--svg-color--745b8c, #745B8C);
  stop-opacity: 0;
}

.wrh5y-bmk {
  stop-color: var(--svg-color--d99386, #D99386);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wvl4ponzh {
  stop-color: var(--svg-color--ffd0bc, #FFD0BC);
}

.x0-05wb5o {
  stop-color: var(--svg-color--62429a, #62429A);
}

.x0hvtbbrr {
  stop-color: var(--svg-color--785e96, #785E96);
  stop-opacity: 0;
}

.x1ls_mb4u {
  d: path("M24.75 19.837a.885.885 0 0 1 .35-1.204l2.609-1.427a.899.899 0 1 1 .856 1.58l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.x4h3z4bif {
  fill: var(--svg-color--000, #000);
  d: path("M13.891 12.488a.64.64 0 0 0-.644-.644a.642.642 0 0 0-.573.94h1.14a.64.64 0 0 0 .077-.296");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmd1de7c {
  stop-color: var(--svg-color--e2ae96, #E2AE96);
}

.xjoxl1baz {
  stop-color: var(--svg-color--76679f, #76679F);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xm7oxtb8r {
  stop-color: var(--svg-color--433169, #433169);
}

.xpxgkfbfk {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.505 12.436l-.862 2.143a.68.68 0 0 0 .657.882h.991a.682.682 0 0 0 .656-.882l-.67-2.143c-.143-.474-.621-.474-.772 0");
}

.xv-pxlqsu {
  stop-color: var(--svg-color--f3c1a8, #F3C1A8);
}

.xyqac8gqa {
  stop-color: var(--svg-color--a680df, #A680DF);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y0cud7bhd {
  stop-color: var(--svg-color--705f9f, #705F9F);
}

.y0d2ypbdf {
  stop-color: var(--svg-color--8b64ce, #8B64CE);
}

.y3cvo6brh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.67 11.6c.08.108-.087.239-.278.381c-.19.143-.331.243-.411.136c-.08-.108.009-.31.2-.452c.19-.143.41-.171.49-.064");
}

.y57xohvpz {
  d: path("M25.5 30.033h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.y5pwnueug {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.355 4.47c.03.307.296 1.458.687 2.156");
}

.yjwkbfbeo {
  stop-color: var(--svg-color--d6af98, #D6AF98);
  stop-opacity: 0;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ypu5blbsz {
  stop-color: var(--svg-color--fbc7b5, #FBC7B5);
}

.yqb6cfbzv {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.014 11.02a1.76 1.76 0 0 1 1.708 1.335a.346.346 0 0 1-.338.43h-2.812a.29.29 0 0 1-.286-.343a1.76 1.76 0 0 1 1.728-1.421");
}

.ywta_-xao {
  d: path("M19.755 12.34a1.06 1.06 0 0 0-.291-.583l-.328.36l.148.287z");
}

.z-bv-oxvq {
  stop-color: var(--svg-color--ffd7c0, #FFD7C0);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zb0hqnb-l {
  stop-color: var(--svg-color--8071aa, #8071AA);
}

.zfxir_qeb {
  d: path("M13.247 11.363a1.125 1.125 0 0 0-1.084 1.422h2.173q.039-.146.04-.297a1.133 1.133 0 0 0-1.13-1.125");
}

.zlawngbku {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
}

.ztga85boj {
  d: path("M10.093 14.746a2.028 2.028 0 1 0 0-4.057a2.028 2.028 0 0 0 0 4.057");
}

</style>
