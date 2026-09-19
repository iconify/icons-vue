<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJKlTZd)"><path fill="url(#iO1mJJb)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#iMaIYQd)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#iB1Ytlc)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#iq6VJQe)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#i6NVboc)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#iPnvn1d)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#iAAmmnd)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#ibjNegT)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#i8AvgCd)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#i2OIkpb)" clip-rule="evenodd" class="b7e8sbbei"/><path fill="url(#ioXbNIe)" clip-rule="evenodd" class="b7e8sbbei"/></g><path fill="url(#iHNqk0X)" class="evso7acss"/><path fill="url(#imqjm9c)" class="evso7acss"/><g filter="url(#iqyIZtx)"><path fill="url(#ia8zscL)" class="i9t6f2bxc"/></g><path fill="url(#ivjsgxd)" class="jcl-2hb7f"/><path fill="url(#iod3k0b)" class="jcl-2hb7f"/><path class="hmnycxx5w"/><path fill="url(#iyhUdBG)" class="cllop4bqc"/><path fill="url(#iyeCLFd)" class="cllop4bqc"/><path fill="url(#i20rlAd)" class="cllop4bqc"/><path fill="url(#iRJv8Rc)" class="cu21d24az"/><path fill="url(#iyAgBob)" class="cu21d24az"/><path fill="url(#iLKBWPD)" class="cu21d24az"/><path fill="url(#i92uFDa)" class="cu21d24az"/><g filter="url(#iKW27se)"><path class="pbxi84b9i"/></g><g filter="url(#i183fsd)"><path fill="url(#i5XOWcD)" class="z-t54tbit"/><path fill="url(#iIuGzte)" class="z-t54tbit"/></g><path fill="url(#iRR6nWc)" class="z-t54tbit"/><g filter="url(#iTTfIib)"><ellipse class="ijlx-8buq"/></g><g filter="url(#icvEjRc)"><path fill="url(#ilz7GNd)" class="k7zk34bqa"/><path fill="url(#isFAYCe)" class="k7zk34bqa"/><path fill="url(#ioWJHub)" class="k7zk34bqa"/><path fill="url(#i9nPv5b)" class="k7zk34bqa"/></g><ellipse fill="url(#iKdWZUd)" class="skhx9acxb"/><ellipse fill="url(#iLpatmc)" class="skhx9acxb"/><rect fill="url(#iWKg6Ke)" class="qhe9mm7xm"/><path fill="url(#iCIUDTd)" class="oumjgbbsr"/><path fill="url(#i9EbKOc)" class="wdqycsape"/><g filter="url(#iUBPsyc)"><path fill="url(#isMn7Dd)" class="u537au68g"/></g><g filter="url(#iVUZUoc)"><path fill="url(#ilZnwAe)" class="q-rok850b"/><path fill="url(#iFzGOgd)" class="q-rok850b"/></g><g filter="url(#i987hrP)"><path class="jp41or55u"/><path fill="url(#i8Rj8iy)" class="em_l9-b0x"/></g><g filter="url(#iw6tnPb)"><path class="kvm0mabyi"/><path fill="url(#iBmbdMe)" class="h8pkbf-mw"/></g><g filter="url(#ilYXobK)"><path fill="url(#i0f0xbb)" class="slies2mux"/><path fill="url(#ijlUPBc)" class="slies2mux"/><path fill="url(#i7oDLtb)" class="slies2mux"/><path fill="url(#iqvsfdb)" class="slies2mux"/><path fill="url(#iEXzPsr)" class="slies2mux"/><path fill="url(#iEMNIYc)" class="slies2mux"/><path fill="url(#irHC5GY)" class="slies2mux"/></g><path fill="url(#i0z251f)" class="slies2mux"/><path fill="url(#imY0Tie)" class="slies2mux"/><g filter="url(#i2ChSBb)"><path class="qw-pefbqb"/></g><path fill="url(#izDgYXb)" class="l79i6ybht"/><path fill="url(#iCFjUhd)" class="l79i6ybht"/><g filter="url(#inNzDWb)"><path class="d-t0gnb5g"/><path fill="url(#iS4z0Vd)" class="w0up-zbrx"/></g><g filter="url(#ibfvDBb)"><path stroke="url(#iHbrooc)" class="ei-19obta"/></g><path class="j2nudi6ts"/><g filter="url(#iMlbhae)"><path class="dry94dbyt"/></g><g filter="url(#i156omr)"><path class="h97g4bbop"/></g><path class="ehixcpwic"/><path fill="url(#iaVDaIc)" class="amod97zvr"/><path class="bxp5an-ep"/><g filter="url(#ib8oVJE)"><path class="ss77apb-p"/><path fill="url(#iKvuZXb)" class="lgb__abit"/></g><g filter="url(#iI6206b)"><path fill="url(#iGeJ5ub)" class="hd3sn2b_v"/></g><path class="qezoyjb5s"/><path fill="url(#iB2mZRb)" class="edo2bs2zu"/><path class="wl4qnubcg"/><g filter="url(#isEd14c)"><path fill="url(#iHMDvmb)" class="ou3345_0z"/></g><g filter="url(#iZDwCte)"><ellipse transform="rotate(-27.914 13.534 9.88)" class="wyl40hu4l"/><ellipse fill="url(#iRWf7zb)" transform="rotate(-27.914 13.534 9.88)" class="wz3qf_bdy"/></g><g filter="url(#iKne68V)"><path class="incrykpwp"/><path fill="url(#idUkeLv)" class="kfr1j3b0f"/></g><g filter="url(#imog7he)"><path class="i281b-bpl"/><path fill="url(#i5qKsed)" class="kwsmp-_oy"/><path fill="url(#iZ4vULQ)" class="kwsmp-_oy"/></g><g filter="url(#i1q6BFc)"><path stroke="url(#iNQSuke)" class="q1asfk6jl"/></g><g filter="url(#i93noqd)"><path class="td255j1vn"/></g><defs><radialGradient id="iMaIYQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.686 13.074)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iB1Ytlc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.87 13.342)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iq6VJQe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.905 8.15)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i6NVboc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.34 7.635)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iPnvn1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.467 2.514)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iAAmmnd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.959 6.816)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ibjNegT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.496 9.722)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i8AvgCd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.638 7.98)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i2OIkpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.72 7.288)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ioXbNIe" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.845 9.686)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iHNqk0X" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5824 -20.8203 0 16 18.372)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="gawd5obvo"/><stop offset="1" class="rn540obxc"/></radialGradient><radialGradient id="imqjm9c" cx="0" cy="0" r="1" gradientTransform="rotate(124.924 1.228 11.052)scale(12.8824 12.131)" gradientUnits="userSpaceOnUse"><stop class="y9rlcreuk"/><stop offset="1" class="xd0kopb5v"/></radialGradient><radialGradient id="ivjsgxd" cx="0" cy="0" r="1" gradientTransform="rotate(123.174 5.837 15.598)scale(11.5365 12.2083)" gradientUnits="userSpaceOnUse"><stop class="r3949-bju"/><stop offset="1" class="s9sui_61e"/></radialGradient><radialGradient id="iod3k0b" cx="0" cy="0" r="1" gradientTransform="rotate(100.184 -.325 14.065)scale(5.30229 7.65346)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="t-ehpbubw"/><stop offset="1" class="h61yu9bmy"/></radialGradient><radialGradient id="iyeCLFd" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 0 0 14.5199 23.18 29.622)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="oj7ch-bkx"/><stop offset="1" class="ce13789qs"/></radialGradient><radialGradient id="i20rlAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.1762 .21924 0 23.68 29.955)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="x8ej_jb7y"/><stop offset="1" class="mjbwacbml"/></radialGradient><radialGradient id="iyAgBob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6875 0 0 -13.3438 9.555 29.779)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="wx3vdcbzg"/><stop offset="1" class="jug-l4bwb"/></radialGradient><radialGradient id="iLKBWPD" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 -1.5668 5.45335 .48945 5.71 29.955)" gradientUnits="userSpaceOnUse"><stop class="x_0jnxbib"/><stop offset="1" class="wn7157b9l"/></radialGradient><radialGradient id="i92uFDa" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 0 0 -15.1051 8.383 29.955)" gradientUnits="userSpaceOnUse"><stop class="ujtti6ofv"/><stop offset="1" class="gewmlvbcg"/></radialGradient><radialGradient id="iRR6nWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 .54687 -.67794 -.87163 19.711 23.404)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="l56m45bvi"/><stop offset="1" class="v2ucwt3jq"/></radialGradient><radialGradient id="isFAYCe" cx="0" cy="0" r="1" gradientTransform="rotate(111.034 1.943 12.516)scale(3.13667 4.32041)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="t6s1vnb2t"/><stop offset="1" class="zi8t_0buy"/></radialGradient><radialGradient id="ioWJHub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -3 0 20.742 15.341)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="mzeokobes"/><stop offset="1" class="qhzdg_bmj"/></radialGradient><radialGradient id="i9nPv5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79294 -6.37953 0 19.492 15.403)" gradientUnits="userSpaceOnUse"><stop class="kuordwbwu"/><stop offset="1" class="mt9_xyb2a"/></radialGradient><radialGradient id="iKdWZUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.363 3.443 13.942)scale(1.76569 1.94865)" gradientUnits="userSpaceOnUse"><stop class="su-lx9b4e"/><stop offset="1" class="fh2jv1bsu"/></radialGradient><radialGradient id="iLpatmc" cx="0" cy="0" r="1" gradientTransform="rotate(111.306 1.436 15.466)scale(1.67712 2.10568)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="otqjsqgnm"/><stop offset="1" class="cz6js0bhr"/></radialGradient><radialGradient id="iWKg6Ke" cx="0" cy="0" r="1" gradientTransform="rotate(41.072 -15.094 28.3)scale(2.76174 3.96201)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="ns_j8fhoj"/><stop offset="1" class="x39b-tbnv"/><stop offset="1" class="fxvwrsuly"/></radialGradient><radialGradient id="ilZnwAe" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.186 -17.187)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iFzGOgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.058 8.892)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i8Rj8iy" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.379 10.685)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iBmbdMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.386 10.573)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i0f0xbb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.846 10.036)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="ijlUPBc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.239 11.398)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i7oDLtb" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.607 17.365)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iqvsfdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 15.987 9.818)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="iEXzPsr" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.327 6.748)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iEMNIYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.289 9.617)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="irHC5GY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.91 9.389)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="i0z251f" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.083 11.105)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="imY0Tie" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.803 4.037)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iS4z0Vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42625 -3.34452 1.30814 -.16672 16.836 12.194)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="epy_aimha"/><stop offset="1" class="rfbnizbpu"/></radialGradient><radialGradient id="iaVDaIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.17 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKvuZXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.941 10.06)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iB2mZRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.805 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRWf7zb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.778 -1.557)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idUkeLv" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.284 -4.118)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i5qKsed" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.117 6.95)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iZ4vULQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.198 3.018)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iJKlTZd" width="15.268" height="15.768" x="8.478" y="1.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="iqyIZtx" width="25.813" height="14.219" x="3.094" y="15.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".125"/></filter><filter id="iKW27se" width="9.1" height="7.705" x="10.989" y="22.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".5"/></filter><filter id="i183fsd" width="7.926" height="6.427" x="12.029" y="22.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.407843 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_938" result="effect2_innerShadow_4002_938"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_938" result="effect3_innerShadow_4002_938"/></filter><filter id="iTTfIib" width="3.095" height="3.11" x="14.16" y="18.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".25"/></filter><filter id="icvEjRc" width="11.606" height="4.825" x="10.289" y="15.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="iUBPsyc" width="3.368" height="3.218" x="9.693" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="iVUZUoc" width="3.218" height="3.468" x="19.206" y="8.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="i987hrP" width="3.148" height="3.148" x="19.241" y="8.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".25"/></filter><filter id="iw6tnPb" width="2.948" height="2.948" x="9.847" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".2"/></filter><filter id="ilYXobK" width="10.191" height="11.277" x="10.892" y="5.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="i2ChSBb" width="2.877" height="3.682" x="14.386" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".25"/></filter><filter id="inNzDWb" width="1.998" height="2.625" x="15.138" y="10.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.631373 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="ibfvDBb" width="3.702" height="1.526" x="14.136" y="12.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".05"/></filter><filter id="iMlbhae" width="3.001" height="1.285" x="16.93" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="i156omr" width="3.001" height="1.285" x="12.044" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/></filter><filter id="ib8oVJE" width=".787" height=".696" x="17.435" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".05"/></filter><filter id="iI6206b" width=".891" height=".913" x="18.275" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".1"/></filter><filter id="isEd14c" width=".986" height="1.04" x="13.832" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".1"/></filter><filter id="iZDwCte" width=".913" height=".704" x="13.078" y="9.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".05"/></filter><filter id="iKne68V" width="4.212" height="4.513" x="9.733" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/><feGaussianBlur result="effect2_foregroundBlur_4002_938" stdDeviation=".15"/></filter><filter id="imog7he" width="8.767" height="5.782" x="12.817" y="2.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_938"/><feGaussianBlur result="effect2_foregroundBlur_4002_938" stdDeviation=".125"/></filter><filter id="i1q6BFc" width="1.145" height="2.31" x="12.796" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".1"/></filter><filter id="i93noqd" width="6.427" height="3.372" x="15.405" y="4.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_938" stdDeviation=".375"/></filter><linearGradient id="iO1mJJb" x1="20.681" x2="13.876" y1="3.621" y2="16.225" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ia8zscL" x1="16" x2="16" y1="16.236" y2="30.341" gradientUnits="userSpaceOnUse"><stop offset=".866" class="tyjpv6bnm"/><stop offset="1" class="xyu2htzlq"/></linearGradient><linearGradient id="iyhUdBG" x1="26.992" x2="26.773" y1="30.247" y2="27.497" gradientUnits="userSpaceOnUse"><stop class="pmf-vsdxp"/><stop offset="1" class="w6_8my7ls"/></linearGradient><linearGradient id="iRJv8Rc" x1="8.586" x2="5.336" y1="25.154" y2="25.154" gradientUnits="userSpaceOnUse"><stop offset=".183" class="annwmpbcg"/><stop offset="1" class="l85-jsb-f"/></linearGradient><linearGradient id="i5XOWcD" x1="18.555" x2="13.805" y1="23.966" y2="27.31" gradientUnits="userSpaceOnUse"><stop class="big423byp"/><stop offset="1" class="zbo4__e4e"/></linearGradient><linearGradient id="iIuGzte" x1="15.992" x2="15.992" y1="22.857" y2="24.201" gradientUnits="userSpaceOnUse"><stop class="ash9yfbkf"/><stop offset="1" class="k-dn1jb7a"/></linearGradient><linearGradient id="ilz7GNd" x1="14.773" x2="20.117" y1="19.06" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="umjrh49bx"/><stop offset="1" class="d7r2s6row"/></linearGradient><linearGradient id="iCIUDTd" x1="8.847" x2="23.223" y1="15.383" y2="15.383" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i9EbKOc" x1="8.846" x2="23.222" y1="15.352" y2="15.352" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="isMn7Dd" x1="9.693" x2="12.652" y1="10.66" y2="10.66" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="izDgYXb" x1="20.375" x2="12.995" y1="10.69" y2="10.69" gradientUnits="userSpaceOnUse"><stop class="z14dz9exi"/><stop offset="1" class="o1uobmugz"/></linearGradient><linearGradient id="iCFjUhd" x1="10.892" x2="12.341" y1="10.377" y2="10.377" gradientUnits="userSpaceOnUse"><stop class="f6x3qhriw"/><stop offset="1" class="onbz4ubrj"/></linearGradient><linearGradient id="iHbrooc" x1="14.923" x2="15.384" y1="14.113" y2="13.401" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="iGeJ5ub" x1="18.947" x2="18.634" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHMDvmb" x1="14.549" x2="14.235" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNQSuke" x1="13.096" x2="13.641" y1="4.375" y2="5.649" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-superhero-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.amod97zvr {
  d: path("M18.171 9.5a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.annwmpbcg {
  stop-color: var(--svg-color--3e80f0, #3E80F0);
}

.ash9yfbkf {
  stop-color: var(--svg-color--40a0f8, #40A0F8);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b7e8sbbei {
  fill-rule: evenodd;
  d: path("M23.173 11.983a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.3 3.3 0 0 0-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 3.218-3.218a3.3 3.3 0 0 0-.323-1.407a.51.51 0 0 1 0-.455M10.913 9.31H10.9l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194A2.3 2.3 0 0 1 11.702 7.3c-.236.122-.79.49-.81 1.438l.01.306z");
}

.big423byp {
  stop-color: var(--svg-color--47a1ff, #47A1FF);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bxp5an-ep {
  fill: var(--svg-color--000, #000);
  d: path("M17.66 10.392a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ce13789qs {
  stop-color: var(--svg-color--528adb, #528ADB);
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

.cllop4bqc {
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.cu21d24az {
  d: path("M8.383 18.468v11.487H4.039v-.036c.22-5.447 1.882-9.174 4.344-11.451");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cz6js0bhr {
  stop-color: var(--svg-color--d79d4a, #D79D4A);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d-t0gnb5g {
  fill: var(--svg-color--f7c1a9, #F7C1A9);
  d: path("m15.642 10.58l-.481 1.537a.488.488 0 0 0 .47.633h.712a.49.49 0 0 0 .47-.633l-.48-1.537c-.103-.34-.584-.34-.691 0");
}

.d7r2s6row {
  stop-color: var(--svg-color--ff3656, #FF3656);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dry94dbyt {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.13 10.004c.265-.467.668-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.496.024.6l-.556.317c-.651-.21-1.372-.24-2.078-.45");
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

.edo2bs2zu {
  d: path("M13.803 9.5a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ehixcpwic {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.378 9.227c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.ei-19obta {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.987 13.485a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.089-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.em_l9-b0x {
  d: path("M20.815 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.epy_aimha {
  stop-color: var(--svg-color--ffceb8, #FFCEB8);
}

.evso7acss {
  d: path("M2.063 29.955c0-1.969.39-6.76 3.216-9.86C8.81 16.222 13.793 15.643 16 15.643s7.19.579 10.721 4.454c2.826 3.1 3.217 7.89 3.217 9.859z");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f6x3qhriw {
  stop-color: var(--svg-color--ab2d46, #AB2D46);
}

.fh2jv1bsu {
  stop-color: var(--svg-color--f2bb43, #F2BB43);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fxvwrsuly {
  stop-color: var(--svg-color--f4b4ab, #F4B4AB);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gawd5obvo {
  stop-color: var(--svg-color--ff3b9a, #FF3B9A);
}

.gewmlvbcg {
  stop-color: var(--svg-color--2154ca, #2154CA);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h61yu9bmy {
  stop-color: var(--svg-color--3a7ad3, #3A7AD3);
  stop-opacity: 0;
}

.h8pkbf-mw {
  d: path("M11.32 11.647a1.074 1.074 0 1 0 .001-2.148a1.074 1.074 0 0 0 0 2.148");
}

.h97g4bbop {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.845 10.004c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.024.6l.556.317c.651-.21 1.372-.24 2.078-.45");
}

.hd3sn2b_v {
  d: path("M18.966 10.274a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmnycxx5w {
  fill: var(--svg-color--4e9eff, #4E9EFF);
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i281b-bpl {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.384 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.i9t6f2bxc {
  d: path("M3.344 29.955c0-1.887.355-6.479 2.92-9.45c3.207-3.715 7.732-4.269 9.736-4.269s6.529.554 9.736 4.269c2.565 2.971 2.92 7.563 2.92 9.45z");
}

.ijlx-8buq {
  cx: 15.708px;
  cy: 20.263px;
  fill: var(--svg-color--2f62b7, #2F62B7);
  rx: 1.048px;
  ry: 1.055px;
}

.incrykpwp {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.918 4.585c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2nudi6ts {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.987 13.485a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.089-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jcl-2hb7f {
  d: path("M16.031 15.638c-6.228 0-11.584 4.188-11.992 14.281v.036h23.984v-.036c-.408-10.093-5.764-14.28-11.992-14.28");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jp41or55u {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.815 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.jug-l4bwb {
  stop-color: var(--svg-color--407dbe, #407DBE);
}

.k-dn1jb7a {
  stop-color: var(--svg-color--4392f9, #4392F9);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k7zk34bqa {
  d: path("m15.992 20.435l-5.04-3.023c-.323-.2-.663-.512-.663-.98c0-.497.585-.533.885-.544l4.818-.078l4.819.078c.3.01.884.047.884.543c0 .469-.34.781-.663.98z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kfr1j3b0f {
  d: path("M10.918 4.585c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kuordwbwu {
  stop-color: var(--svg-color--bb1135, #BB1135);
}

.kvm0mabyi {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.32 11.647a1.074 1.074 0 1 0 .001-2.148a1.074 1.074 0 0 0 0 2.148");
}

.kwsmp-_oy {
  d: path("M15.384 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l56m45bvi {
  stop-color: var(--svg-color--53b7ff, #53B7FF);
}

.l79i6ybht {
  d: path("M10.912 9.31H10.9l.077 2.01h.315q.282 0 .534.12l.247.12c.09.04.178.08.267.11l.218.07c.425.13.88.14 1.306.02l.277-.08c.108-.03.217-.07.316-.12l.228-.11q.252-.12.534-.12h.346l.165-.668c.118-.39.264-.39.382 0l.094.668h.467q.282 0 .534.12l.208.1c.109.05.227.1.346.13l.307.09c.425.12.89.11 1.305-.04l.178-.06l.238-.09l.267-.12q.252-.12.534-.12h.394l.099-2.554l-.007-.106h-.387c-.247-.02-.494-.1-.712-.24l-.05-.03a2.2 2.2 0 0 0-.553-.28a2.16 2.16 0 0 0-1.306-.04l-.129.03c-.237.07-.465.17-.672.32s-.456.22-.713.22h-1.226c-.258 0-.505-.08-.712-.22l-.01-.01a2.3 2.3 0 0 0-.643-.31l-.09-.03c-.425-.12-.88-.12-1.305.02l-.04.01c-.207.07-.405.17-.593.29l-.03.03c-.217.14-.465.22-.722.22h-.288l-.003.08l.01.305z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l85-jsb-f {
  stop-color: var(--svg-color--3e77d8, #3E77D8);
}

.lgb__abit {
  d: path("M18.106 9.688c.063.085-.07.189-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
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

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mjbwacbml {
  stop-color: var(--svg-color--286adf, #286ADF);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9_xyb2a {
  stop-color: var(--svg-color--bb1135, #BB1135);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzeokobes {
  stop-color: var(--svg-color--f04451, #F04451);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.ns_j8fhoj {
  stop-color: var(--svg-color--c38389, #C38389);
}

.o1uobmugz {
  stop-color: var(--svg-color--c31251, #C31251);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj7ch-bkx {
  stop-color: var(--svg-color--528adb, #528ADB);
  stop-opacity: 0;
}

.onbz4ubrj {
  stop-color: var(--svg-color--ba3950, #BA3950);
  stop-opacity: 0;
}

.otqjsqgnm {
  stop-color: var(--svg-color--f6c546, #F6C546);
  stop-opacity: 0;
}

.ou3345_0z {
  d: path("M14.619 10.287c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oumjgbbsr {
  d: path("M16.386 15.353c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbxi84b9i {
  fill: var(--svg-color--2f63d5, #2F63D5);
  d: path("M12.875 23.42a.885.885 0 0 0-.763 1.333l2.143 3.638a1.49 1.49 0 0 0 2.568 0l2.142-3.638a.885.885 0 0 0-.762-1.334z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmf-vsdxp {
  stop-color: var(--svg-color--4d87f8, #4D87F8);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.q-rok850b {
  d: path("M20.815 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.q1asfk6jl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.096 4.031c.023.243.235 1.157.545 1.71");
}

.qezoyjb5s {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.596 9.227c-.653 0-1.205.45-1.355 1.06c-.044.173.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.qhe9mm7xm {
  width: 4.109px;
  height: 5.399px;
  x: 13.933px;
  y: 13.298px;
  rx: 2.055px;
}

.qhzdg_bmj {
  stop-color: var(--svg-color--f04451, #F04451);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw-pefbqb {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.595 10.35l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r3949-bju {
  stop-color: var(--svg-color--4690e6, #4690E6);
}

.rfbnizbpu {
  stop-color: var(--svg-color--ffceb8, #FFCEB8);
  stop-opacity: 0;
}

.rn540obxc {
  stop-color: var(--svg-color--ee344d, #EE344D);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s9sui_61e {
  stop-color: var(--svg-color--3e75e1, #3E75E1);
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.skhx9acxb {
  cx: 15.992px;
  cy: 20.17px;
  rx: 1.048px;
  ry: 1.055px;
}

.slies2mux {
  d: path("M10.9 9.31h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684c-2.672 0-4.86-1.882-4.983-4.684z");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ss77apb-p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.106 9.688c.063.085-.07.189-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su-lx9b4e {
  stop-color: var(--svg-color--fff14e, #FFF14E);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t-ehpbubw {
  stop-color: var(--svg-color--3062ac, #3062AC);
}

.t6s1vnb2t {
  stop-color: var(--svg-color--780438, #780438);
}

.td255j1vn {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.394 6.392l-1.426.262a.688.688 0 1 1-.125-1.364h2.341c1.384 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tyjpv6bnm {
  stop-color: var(--svg-color--790b2c, #790B2C);
}

.u537au68g {
  d: path("M11.302 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ujtti6ofv {
  stop-color: var(--svg-color--2154ca, #2154CA);
}

.umjrh49bx {
  stop-color: var(--svg-color--ce1f66, #CE1F66);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v2ucwt3jq {
  stop-color: var(--svg-color--49a3ff, #49A3FF);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w0up-zbrx {
  d: path("m15.642 10.58l-.481 1.537a.488.488 0 0 0 .47.633h.712a.49.49 0 0 0 .47-.633l-.48-1.537c-.103-.34-.584-.34-.691 0");
}

.w6_8my7ls {
  stop-color: var(--svg-color--4b99ff, #4B99FF);
  stop-opacity: 0;
}

.wdqycsape {
  d: path("M16.056 15.353h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.wl4qnubcg {
  fill: var(--svg-color--000, #000);
  d: path("M14.314 10.392a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.235");
}

.wn7157b9l {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
  stop-opacity: 0;
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wx3vdcbzg {
  stop-color: var(--svg-color--407dbe, #407DBE);
  stop-opacity: 0;
}

.wyl40hu4l {
  cx: 13.534px;
  cy: 9.88px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wz3qf_bdy {
  cx: 13.534px;
  cy: 9.88px;
  rx: 0.39px;
  ry: 0.197px;
}

.x_0jnxbib {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
}

.x39b-tbnv {
  stop-color: var(--svg-color--e1a18f, #E1A18F);
}

.x8ej_jb7y {
  stop-color: var(--svg-color--286adf, #286ADF);
}

.xd0kopb5v {
  stop-color: var(--svg-color--bf2370, #BF2370);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xyu2htzlq {
  stop-color: var(--svg-color--790b2c, #790B2C);
  stop-opacity: 0;
}

.y9rlcreuk {
  stop-color: var(--svg-color--bf2370, #BF2370);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z-t54tbit {
  d: path("M13.13 22.998a.95.95 0 0 0-.818 1.432l2.302 3.907a1.6 1.6 0 0 0 2.757 0l2.301-3.907a.95.95 0 0 0-.819-1.433z");
}

.z14dz9exi {
  stop-color: var(--svg-color--ff1781, #FF1781);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbo4__e4e {
  stop-color: var(--svg-color--3f83f1, #3F83F1);
}

.zi8t_0buy {
  stop-color: var(--svg-color--780438, #780438);
  stop-opacity: 0;
}

</style>
