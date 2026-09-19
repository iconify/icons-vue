<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7EQPHb)"><path fill="url(#iWhfdZc)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#ilz52cP)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iicIhLb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#ij0sgad)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#igJizVc)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iWm3AJc)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#i8a0AQb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#ikYH5Ec)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iK0sl1C)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iHXHk4b)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iOzjCzd)" clip-rule="evenodd" class="zm9zkcl5b"/></g><path class="d_rfnfrcy"/><path class="w-ckuacsw"/><g filter="url(#ijSN4ha)"><path class="t0i8q5bxh"/><path fill="url(#i1pVYse)" class="o_hp5nbjg"/></g><path class="ra3fmdbhh"/><path fill="url(#iPyW2Id)" class="o93ji_bej"/><path fill="url(#iVlX5Fb)" class="o93ji_bej"/><g filter="url(#iJQIs1d)"><path class="xc0pf8zxu"/></g><path class="pu1qalb0n"/><path fill="url(#ieyaRhd)" class="pcr8w9bct"/><path fill="url(#i9fb3ne)" class="pcr8w9bct"/><path fill="url(#iek6ihd)" class="pcr8w9bct"/><path fill="url(#izgSJzU)" class="pcr8w9bct"/><path class="myif5tbjr"/><path fill="url(#iNC83fb)" class="u1ssmd66p"/><path fill="url(#iBwD5cu)" class="u1ssmd66p"/><g filter="url(#icObKRb)"><path class="xqme1t_en"/></g><path fill="url(#icWbAmd)" class="cge-036tr"/><path fill="url(#iJO9Dac)" class="cge-036tr"/><path fill="url(#iApyzzd)" class="cge-036tr"/><path fill="url(#ivzWvsb)" class="cge-036tr"/><g filter="url(#ius5kfc)"><path fill="url(#iCEVb2b)" class="qr3eebgfz"/><path fill="url(#iS5fSJc)" class="qr3eebgfz"/></g><path fill="url(#iO1McLA)" class="qr3eebgfz"/><path fill="url(#iIFRdJe)" class="qr3eebgfz"/><path fill="url(#iZS1s2p)" class="i0vp1so6w"/><g filter="url(#i4YK8Oe)"><path class="ise8hkbqb"/></g><path fill="url(#iiFwxIb)" class="ukvj5-vlj"/><path fill="url(#iNo9Upb)" class="ukvj5-vlj"/><g filter="url(#ijMNVub)"><path class="hm4ptbkef"/></g><path fill="url(#imXX7Fy)" class="r7p4z7bsm"/><path fill="url(#iFVyysb)" class="d8xf2ibmq"/><g filter="url(#iYcGlHI)"><path fill="url(#iZDS3Zb)" class="qrmj1y8xw"/></g><g filter="url(#igf7bKc)"><path fill="url(#ifLF52D)" class="ymsp3kbav"/><path fill="url(#i025iUH)" class="ymsp3kbav"/></g><g filter="url(#iEdWNDF)"><path class="qj41u_cgb"/><path fill="url(#iXRKmFc)" class="ojwkb-b4s"/></g><g filter="url(#i7rRgec)"><path class="tdx0miyyu"/><path fill="url(#ikYsBPL)" class="zjcs0bbar"/></g><g filter="url(#iTF69yB)"><path fill="url(#iaBC7Bc)" class="j1j51bc4m"/><path fill="url(#i7GXGRn)" class="j1j51bc4m"/><path fill="url(#iOxM0qd)" class="j1j51bc4m"/><path fill="url(#iHxIhgb)" class="j1j51bc4m"/><path fill="url(#iFQyxxc)" class="j1j51bc4m"/><path fill="url(#itYDL2d)" class="j1j51bc4m"/><path fill="url(#imu6Qsc)" class="j1j51bc4m"/></g><path fill="url(#iiquu3c)" class="j1j51bc4m"/><path fill="url(#iceCQKd)" class="j1j51bc4m"/><g filter="url(#ibnK92c)"><path class="cssy8uj-v"/></g><g filter="url(#ii6Raed)"><path class="rphrai62r"/><path fill="url(#ik9agRc)" class="xc4tawbvb"/><path fill="url(#iFGmedb)" class="xc4tawbvb"/><path fill="url(#iCUOSjS)" class="xc4tawbvb"/><path fill="url(#iY3ZGGd)" class="xc4tawbvb"/></g><g filter="url(#icvKwvb)"><path stroke="url(#ikT6CDd)" class="lmzxl_kgr"/></g><path class="ikpy-qbyu"/><g filter="url(#iLh2eRt)"><path class="oief3_b-g"/></g><g filter="url(#iz2sBCb)"><path class="atcofactt"/></g><g filter="url(#iYh0D1c)"><path class="bjc54zb1k"/></g><g filter="url(#ixzyzwd)"><path clip-rule="evenodd" class="ad3wh2bco"/></g><path class="nv-tm3b_c"/><path fill="url(#ivy8uXd)" class="r0w13r7uj"/><path class="umgvlrbgn"/><g filter="url(#iNCpZlB)"><path class="bmuzas5gv"/><path fill="url(#iSxL7AH)" class="ffhuevyci"/></g><g filter="url(#i3i8Shc)"><path fill="url(#iGh2oyc)" class="vy3y1vbex"/></g><path class="hil4-np7l"/><path fill="url(#izqF4vd)" class="t_70vht6h"/><path class="q3bc6bbmg"/><g filter="url(#iDc782b)"><path fill="url(#icnlnye)" class="tkifgyigj"/></g><g filter="url(#iNR6Foc)"><ellipse transform="rotate(-27.914 14.922 5.528)" class="u-feptipi"/><ellipse fill="url(#i8RfYrc)" transform="rotate(-27.914 14.922 5.528)" class="bmn6q0bjm"/></g><g filter="url(#id2HU0b)"><path class="hv20zkbdi"/><path fill="url(#iXYDCBc)" class="d98v_ccwx"/><path fill="url(#iU6BZPZ)" class="d98v_ccwx"/></g><g filter="url(#iluFDFd)"><path class="fg_-lxjey"/></g><defs><radialGradient id="ilz52cP" cx="0" cy="0" r="1" gradientTransform="matrix(-.26505 2.0026 -2.50165 -.3311 15.868 6.931)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iicIhLb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 6.238 5.76)scale(1.52746 2.00696)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ij0sgad" cx="0" cy="0" r="1" gradientTransform="matrix(-.57427 .75098 -.57664 -.44096 13.873 5.93)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="igJizVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56692 .92768 -.65346 -.39934 14.071 5.039)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iWm3AJc" cx="0" cy="0" r="1" gradientTransform="matrix(.60373 1.14855 -1.59437 .83807 14.454 2.293)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i8a0AQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.63314 .63318 -.88485 -.8848 18.562 3.206)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ikYH5Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.80984 .23559 -.4913 -1.68887 19.298 5.458)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iK0sl1C" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23686 .30923 -.39392 -1.57558 19.033 6.96)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iHXHk4b" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 10.61 -4.272)scale(1.23007 .97291)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iOzjCzd" cx="0" cy="0" r="1" gradientTransform="matrix(.6606 .0693 -.11228 1.07037 13.302 5.443)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i1pVYse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="t-6dngxci"/><stop offset="1" class="f43wwdo6w"/></radialGradient><radialGradient id="iPyW2Id" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="sf5s7sb7p"/><stop offset="1" class="s-pdaw7zb"/></radialGradient><radialGradient id="iVlX5Fb" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.319 18.877)" gradientUnits="userSpaceOnUse"><stop class="st9dtfbya"/><stop offset="1" class="ix025ipjh"/></radialGradient><radialGradient id="ieyaRhd" cx="0" cy="0" r="1" gradientTransform="rotate(107.067 2.409 10.603)scale(1.86331 .9169)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="mwlubcb3u"/><stop offset="1" class="sf6dqgv3q"/></radialGradient><radialGradient id="i9fb3ne" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84619 0 0 -3.93164 15.377 12.374)" gradientUnits="userSpaceOnUse"><stop offset=".865" class="k359d0bjg"/><stop offset="1" class="zqan0v-dy"/></radialGradient><radialGradient id="iek6ihd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.683)" gradientUnits="userSpaceOnUse"><stop class="b9nndyb1o"/><stop offset="1" class="aslchbbcc"/></radialGradient><radialGradient id="iNC83fb" cx="0" cy="0" r="1" gradientTransform="matrix(1.08228 -.29102 1.20718 4.48944 18.794 11.828)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="a76ibt5dn"/><stop offset="1" class="s61flvbkc"/></radialGradient><radialGradient id="iJO9Dac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 17.953)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="iApyzzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.075 28.316)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="ivzWvsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.406)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iS5fSJc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.454 8.152)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="elt890uby"/><stop offset="1" class="r2rrbr4ji"/></radialGradient><radialGradient id="iIFRdJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 -7.88477 10.52054 -1.23005 16.423 15.796)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="kqc1q6b3u"/><stop offset=".967" class="dpe-7hbaw"/></radialGradient><radialGradient id="iZS1s2p" cx="0" cy="0" r="1" gradientTransform="matrix(1.42712 .66406 -.8419 1.8093 15.444 8.724)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="s3cq66b1z"/><stop offset="1" class="lo1tb_bzl"/></radialGradient><radialGradient id="iNo9Upb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.264)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="ifLF52D" cx="0" cy="0" r="1" gradientTransform="matrix(.80251 -.89454 1.0922 .97983 17.98 6.26)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="i025iUH" cx="0" cy="0" r="1" gradientTransform="matrix(.57796 .32395 -.09159 .1634 18.227 5.094)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iXRKmFc" cx="0" cy="0" r="1" gradientTransform="matrix(.66323 -.04933 .03857 .51846 17.93 5.882)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="ikYsBPL" cx="0" cy="0" r="1" gradientTransform="matrix(-.5301 0 0 -.41818 13.979 5.832)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iaBC7Bc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.014 4.692)scale(3.14584 4.21065)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="i7GXGRn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52034 .19816 -.21873 -1.67819 17.428 6.195)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iOxM0qd" cx="0" cy="0" r="1" gradientTransform="rotate(-70.959 13.661 -6.083)scale(1.76024 2.23342)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iHxIhgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.95385 -3.41919 0 16 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="ila67hb-y"/></radialGradient><radialGradient id="iFQyxxc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03335 .59528 -1.0249 -5.2225 16.795 6.357)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="itYDL2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50548 .62037 0 17.01 5.412)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="imu6Qsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57653 .66074 0 15.088 5.312)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iiquu3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.56457 0 0 -2.83125 18.238 6.066)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iceCQKd" cx="0" cy="0" r="1" gradientTransform="matrix(.57652 1.75702 -3.06095 1.00438 15.04 2.961)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="ik9agRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2001 -.89784 .2767 -.06167 16.345 6.385)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iY3ZGGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.34236 0 0 -.09571 16.24 6.478)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="ivy8uXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35637 -.56685 0 16.958 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSxL7AH" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 9.802 -1.325)scale(.16616 .22877)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izqF4vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35638 -.56686 0 15.042 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8RfYrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0034 -.21702 .26087 -.00408 14.916 5.666)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXYDCBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92769 1.92897 -3.15375 -1.51671 16.84 2.351)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iU6BZPZ" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 6.968 8.16)scale(.60762 1.30724)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="i7EQPHb" width="6.847" height="7.347" x="12.702" y="1.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="ijSN4ha" width="2.311" height="8.028" x="11.403" y="12.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.74902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="iJQIs1d" width="1.437" height="7.032" x="19.118" y="11.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".25"/></filter><filter id="icObKRb" width="6.169" height="12.453" x="13.016" y="15.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="ius5kfc" width="6.517" height="7.694" x="12.941" y="8.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="i4YK8Oe" width="3.316" height="1.848" x="12.434" y="28.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="ijMNVub" width="6.594" height="13.766" x="12.841" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".5"/></filter><filter id="iYcGlHI" width="1.564" height="1.414" x="13.235" y="5.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="igf7bKc" width="1.414" height="1.664" x="17.414" y="4.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="iEdWNDF" width="1.944" height="1.944" x="17.149" y="4.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".25"/></filter><filter id="i7rRgec" width="1.744" height="1.744" x="13.079" y="4.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".2"/></filter><filter id="iTF69yB" width="4.476" height="5.178" x="13.762" y="3.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="ibnK92c" width="1.825" height="2.178" x="15.016" y="5.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".25"/></filter><filter id="ii6Raed" width="1.025" height="1.378" x="15.488" y="5.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".05"/></filter><filter id="icvKwvb" width="1.701" height=".745" x="15.15" y="6.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".05"/></filter><filter id="iLh2eRt" width="1.431" height=".565" x="16.302" y="5.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="iz2sBCb" width="1.431" height=".565" x="14.268" y="5.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="iYh0D1c" width="1.19" height=".591" x="14.327" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="ixzyzwd" width="1.19" height=".591" x="16.707" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/></filter><filter id="iNCpZlB" width=".458" height=".418" x="16.58" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".05"/></filter><filter id="i3i8Shc" width=".616" height=".625" x="16.893" y="5.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".1"/></filter><filter id="iDc782b" width=".658" height=".681" x="14.941" y="5.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".1"/></filter><filter id="iNR6Foc" width=".513" height=".422" x="14.666" y="5.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".05"/></filter><filter id="id2HU0b" width="4.059" height="2.67" x="14.439" y="2.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_183"/><feGaussianBlur result="effect2_foregroundBlur_4002_183" stdDeviation=".075"/></filter><filter id="iluFDFd" width="2.664" height="1.322" x="15.824" y="3.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_183" stdDeviation=".125"/></filter><linearGradient id="iWhfdZc" x1="18.062" x2="15.072" y1="2.779" y2="8.315" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="izgSJzU" x1="12.466" x2="12.466" y1="12.632" y2="12.474" gradientUnits="userSpaceOnUse"><stop class="d8l0ribxz"/><stop offset="1" class="sgj6b5b-t"/></linearGradient><linearGradient id="iBwD5cu" x1="19.747" x2="19.747" y1="12.632" y2="12.394" gradientUnits="userSpaceOnUse"><stop class="w2wdskbew"/><stop offset="1" class="lj8hkjeee"/></linearGradient><linearGradient id="icWbAmd" x1="16" x2="16" y1="15.863" y2="16.296" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iCEVb2b" x1="16" x2="16" y1="8.953" y2="15.914" gradientUnits="userSpaceOnUse"><stop class="qb52yacny"/><stop offset="1" class="k3iqnbc3x"/></linearGradient><linearGradient id="iO1McLA" x1="17.173" x2="17.173" y1="15.914" y2="15.654" gradientUnits="userSpaceOnUse"><stop offset=".068" class="d10os3b5g"/><stop offset="1" class="tfix0o_9x"/></linearGradient><linearGradient id="iiFwxIb" x1="18.247" x2="16.5" y1="29.578" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="imXX7Fy" x1="12.866" x2="19.137" y1="7.821" y2="7.821" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iFVyysb" x1="12.866" x2="19.137" y1="7.807" y2="7.807" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iZDS3Zb" x1="13.235" x2="14.535" y1="5.871" y2="5.871" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iFGmedb" x1="15.588" x2="16" y1="6.417" y2="6.417" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iCUOSjS" x1="16" x2="16" y1="6.768" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ikT6CDd" x1="15.532" x2="15.735" y1="7.387" y2="7.074" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="iGh2oyc" x1="17.3" x2="17.162" y1="5.594" y2="5.679" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icnlnye" x1="15.368" x2="15.23" y1="5.594" y2="5.679" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-standing-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a76ibt5dn {
  stop-color: var(--svg-color--624da1, #624DA1);
}

.ad3wh2bco {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m17.64 4.85l-.062.102za.118.118 0 0 1-.12.202h-.001l-.002-.002l-.05-.025a1 1 0 0 0-.15-.06a1 1 0 0 0-.47-.04a.118.118 0 0 1-.042-.232c.226-.04.434 0 .584.048a1.4 1.4 0 0 1 .245.105l.004.002z");
}

.aslchbbcc {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
  stop-opacity: 0;
}

.atcofactt {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.498 5.582c-.116-.205-.293-.367-.675-.367a.73.73 0 0 0-.471.162c-.118.096-.103.218-.011.264l.244.14c.287-.093.603-.106.913-.199");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b9nndyb1o {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
}

.bjc54zb1k {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m14.508 5.051l-.002.002a.118.118 0 0 1-.122-.202h.001l.001-.002l.005-.002l.014-.008l.05-.026a1.4 1.4 0 0 1 .18-.07c.15-.048.359-.089.584-.049a.118.118 0 1 1-.04.232a1 1 0 0 0-.472.04a1 1 0 0 0-.19.08z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bmn6q0bjm {
  cx: 14.922px;
  cy: 5.528px;
  rx: 0.171px;
  ry: 0.087px;
}

.bmuzas5gv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.93 5.443c.029.038-.03.083-.096.133c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.157c.066-.05.143-.06.17-.023");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cge-036tr {
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
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

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cssy8uj-v {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.828 5.735l-.3.746a.237.237 0 0 0 .228.307h.345a.238.238 0 0 0 .23-.307l-.234-.746c-.05-.166-.217-.166-.27 0");
}

.d_rfnfrcy {
  fill: var(--svg-color--b87e78, #B87E78);
  d: path("M12.668 19.011a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.113a.32.32 0 0 0-.074-.301a9 9 0 0 1-.355-.344");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d10os3b5g {
  stop-color: var(--svg-color--614699, #614699);
}

.d8l0ribxz {
  stop-color: var(--svg-color--482f7c, #482F7C);
}

.d8xf2ibmq {
  d: path("M16.01 7.808h-.017c.044 0 .083 0 .127.004q-.054-.005-.11-.004");
}

.d98v_ccwx {
  d: path("M15.735 2.41c-.498-.11-.944.387-.996.57c.462 1.558 1.631 1.473 2.785 1.345c.69-.077.766.238.825.39c0-1.728-1.47-2.052-2.602-2.302z");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dpe-7hbaw {
  stop-color: var(--svg-color--271a45, #271A45);
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

.elt890uby {
  stop-color: var(--svg-color--9e85d7, #9E85D7);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f43wwdo6w {
  stop-color: var(--svg-color--d0756e, #D0756E);
  stop-opacity: 0;
}

.ffhuevyci {
  d: path("M16.93 5.443c.029.038-.03.083-.096.133c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.157c.066-.05.143-.06.17-.023");
}

.fg_-lxjey {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.057 3.996l-.626.115a.302.302 0 1 1-.055-.6h1.028c.608 0 .81.613.834.823a1.38 1.38 0 0 0-1.18-.338");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hil4-np7l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.95 5.241a.614.614 0 0 0-.595.465a.12.12 0 0 0 .117.15h.98a.1.1 0 0 0 .1-.12a.615.615 0 0 0-.602-.495");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hm4ptbkef {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("M13.841 16.234L14.31 28h.812V17.39h2.203V28h.672l.438-11.766z");
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hv20zkbdi {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.735 2.41c-.498-.11-.944.387-.996.57c.462 1.558 1.631 1.473 2.785 1.345c.69-.077.766.238.825.39c0-1.728-1.47-2.052-2.602-2.302z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i0vp1so6w {
  d: path("M15.129 7.226h1.742v1.352a.871.871 0 0 1-1.742 0z");
}

.ikpy-qbyu {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16 7.111a1.3 1.3 0 0 1-.624-.151c-.062-.032-.129.039-.09.096a.848.848 0 0 0 1.428 0c.038-.06-.028-.128-.09-.096c-.18.096-.393.151-.624.151");
}

.ila67hb-y {
  stop-color: var(--svg-color--c58791, #C58791);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ise8hkbqb {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.671v.243H15.5v-1.598h-1.992c-.102.367-.574.754-.817.914a.54.54 0 0 0-.257.441");
}

.ix025ipjh {
  stop-color: var(--svg-color--d48f89, #D48F89);
  stop-opacity: 0;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j1j51bc4m {
  d: path("M13.765 5.278h.006l-.005-.117l-.004-.134c.009-.417.252-.578.356-.632l.022-.01l.023-.008c.234-.108.423-.296.522-.542l.036-.086a.116.116 0 0 1 .203-.022c.315.462.842.735 1.4.735h1.415c.08 0 .476.038.5.585l-.053 1.35c-.054 1.231-1.015 2.058-2.189 2.058c-1.173 0-2.135-.827-2.189-2.058z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k359d0bjg {
  stop-color: var(--svg-color--645b87, #645B87);
  stop-opacity: 0;
}

.k3iqnbc3x {
  stop-color: var(--svg-color--7759b9, #7759B9);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kqc1q6b3u {
  stop-color: var(--svg-color--4b3677, #4B3677);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
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

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj8hkjeee {
  stop-color: var(--svg-color--6c5ca2, #6C5CA2);
  stop-opacity: 0;
}

.lmzxl_kgr {
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16 7.111a1.3 1.3 0 0 1-.624-.151c-.062-.032-.129.039-.09.096a.848.848 0 0 0 1.428 0c.038-.06-.028-.128-.09-.096c-.18.096-.393.151-.624.151Z");
}

.lo1tb_bzl {
  stop-color: var(--svg-color--fab5a2, #FAB5A2);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mwlubcb3u {
  stop-color: var(--svg-color--4a367d, #4A367D);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.myif5tbjr {
  fill: var(--svg-color--8b7dbc, #8B7DBC);
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nv-tm3b_c {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.05 5.241c.287 0 .53.198.595.465a.12.12 0 0 1-.117.15h-.98a.1.1 0 0 1-.1-.12a.614.614 0 0 1 .602-.495");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o_hp5nbjg {
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.o93ji_bej {
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oief3_b-g {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.502 5.582c.116-.205.294-.367.675-.367c.167 0 .328.047.471.162c.118.096.102.218.011.264l-.244.14c-.287-.093-.603-.106-.913-.199");
}

.ojwkb-b4s {
  d: path("M18.12 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pcr8w9bct {
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pu1qalb0n {
  fill: var(--svg-color--64558f, #64558F);
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.q3bc6bbmg {
  fill: var(--svg-color--000, #000);
  d: path("M15.265 5.753c0-.125-.1-.225-.224-.225a.224.224 0 0 0-.2.328h.398a.2.2 0 0 0 .026-.103");
}

.qb52yacny {
  stop-color: var(--svg-color--8467c1, #8467C1);
}

.qj41u_cgb {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M18.12 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qr3eebgfz {
  d: path("M12.941 11.378a3.059 3.059 0 0 1 6.118 0v4.442a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.qrmj1y8xw {
  d: path("M13.942 6.54a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.413");
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

.r0w13r7uj {
  d: path("M16.96 5.36a.392.392 0 0 1 .377.496h-.757a.394.394 0 0 1 .38-.495");
}

.r2rrbr4ji {
  stop-color: var(--svg-color--886cc6, #886CC6);
  stop-opacity: 0;
}

.r7p4z7bsm {
  d: path("M16.155 7.808q.164.008.336.021c-.114-.008-.223-.017-.336-.021");
}

.ra3fmdbhh {
  fill: var(--svg-color--facbb3, #FACBB3);
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.rphrai62r {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.832 5.674l-.233.746a.237.237 0 0 0 .228.308h.346a.238.238 0 0 0 .228-.308l-.233-.746c-.05-.166-.284-.166-.336 0");
}

.s-pdaw7zb {
  stop-color: var(--svg-color--ff9682, #FF9682);
  stop-opacity: 0;
}

.s3cq66b1z {
  stop-color: var(--svg-color--dc9795, #DC9795);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s61flvbkc {
  stop-color: var(--svg-color--7361ab, #7361AB);
  stop-opacity: 0;
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sf5s7sb7p {
  stop-color: var(--svg-color--ff9682, #FF9682);
}

.sf6dqgv3q {
  stop-color: var(--svg-color--4a367d, #4A367D);
  stop-opacity: 0;
}

.sgj6b5b-t {
  stop-color: var(--svg-color--655690, #655690);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
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

.st9dtfbya {
  stop-color: var(--svg-color--d48f89, #D48F89);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t_70vht6h {
  d: path("M15.04 5.36a.392.392 0 0 0-.377.496h.757a.395.395 0 0 0-.38-.495");
}

.t-6dngxci {
  stop-color: var(--svg-color--d0756e, #D0756E);
}

.t0i8q5bxh {
  fill: var(--svg-color--e3ab9b, #E3AB9B);
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tdx0miyyu {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M13.95 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.tfix0o_9x {
  stop-color: var(--svg-color--7c63b5, #7C63B5);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tkifgyigj {
  d: path("M15.399 5.707c0-.127-.103-.212-.131-.237l-.127.122l.078.16z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u-feptipi {
  cx: 14.922px;
  cy: 5.528px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.171px;
  ry: 0.087px;
}

.u1ssmd66p {
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ukvj5-vlj {
  d: path("M19.566 29.671v.243H16.5v-1.598h1.992c.102.367.574.754.817.914c.186.123.257.3.257.441");
}

.umgvlrbgn {
  fill: var(--svg-color--000, #000);
  d: path("M16.735 5.753c0-.125.1-.225.224-.225a.224.224 0 0 1 .2.328h-.397a.2.2 0 0 1-.027-.103");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vy3y1vbex {
  d: path("M17.309 5.701a.37.37 0 0 0-.102-.203l-.114.125l.051.1z");
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w-ckuacsw {
  fill: var(--svg-color--d89888, #D89888);
  d: path("M19.333 19.011a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.113a.32.32 0 0 1 .074-.301c.083-.077.271-.253.355-.344");
}

.w2wdskbew {
  stop-color: var(--svg-color--503a89, #503A89);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xc0pf8zxu {
  stroke: var(--svg-color--ffc9b6, #FFC9B6);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.767 12.193c.104 1.156.25 3.975 0 6");
}

.xc4tawbvb {
  d: path("m15.832 5.674l-.233.746a.237.237 0 0 0 .228.308h.346a.238.238 0 0 0 .228-.308l-.233-.746c-.05-.166-.284-.166-.336 0");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xqme1t_en {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.ymsp3kbav {
  d: path("M18.12 6.54a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.413");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.zjcs0bbar {
  d: path("M13.95 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.zm9zkcl5b {
  fill-rule: evenodd;
  d: path("M19.156 6.452a1.44 1.44 0 0 0 .024-1.2h.003a1.4 1.4 0 0 0-.124-.226v-.001a1.4 1.4 0 0 1-.232-.778v-.005c0-.8-.649-1.449-1.449-1.449a.24.24 0 0 1-.2-.102a1.452 1.452 0 0 0-2.356 0a.25.25 0 0 1-.2.102h-.037a1.45 1.45 0 0 0-1.412 1.45v.004c0 .275-.08.547-.231.778l-.001.001a1.45 1.45 0 0 0-.097 1.426a.23.23 0 0 1 0 .2a1.41 1.41 0 0 0 1.271 2.032h3.77a1.412 1.412 0 0 0 1.271-2.032a.23.23 0 0 1 0-.2m-5.385-1.174h-.006l.527 1.035c.054 1.23.535 0 1.708 0s1.685 1.37 1.74.139l.498-1.405c-.023-.546-.42-.585-.499-.585h-1.414a1.7 1.7 0 0 1-1.401-.735a.116.116 0 0 0-.203.023l-.036.085a1 1 0 0 1-.522.542l-.023.009l-.022.009c-.104.054-.347.215-.356.632l.004.134z");
}

.zqan0v-dy {
  stop-color: var(--svg-color--645b87, #645B87);
}

</style>
