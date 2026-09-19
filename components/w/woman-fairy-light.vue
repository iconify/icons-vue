<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAy6hEE)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iNR2fXu)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#imGabCe)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#i4lLjJs)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#i582jjc)"><path class="er079sbvz"/></g><g filter="url(#icEILcd)"><path class="ytl8wkbiv"/></g><g filter="url(#iJ3eXbc)"><path class="m8pucsqyt"/></g><g filter="url(#iaeF3gc)"><path class="pv3dgeoha"/></g><g filter="url(#iLBdh0d)"><path fill="url(#itMYOMb)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#iwm4Qhc)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#ifK6P7b)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#i3F8fyb)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#i2YtAnd)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#iWKwshe)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#ix4KcxJ)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#iQeDd9b)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#icWnIyo)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#i4HKNQe)" clip-rule="evenodd" class="tt1u2qbmw"/><path fill="url(#iZGqxTd)" clip-rule="evenodd" class="tt1u2qbmw"/></g><g filter="url(#ieUKStc)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#i8y9yrc)"><path fill="url(#ioitlCc)" class="dv6-6mbxj"/></g><path fill="url(#ipQ5Pnc)" class="dv6-6mbxj"/><path fill="url(#i8KfH3d)" class="dv6-6mbxj"/><path fill="url(#iEdEbnd)" class="dv6-6mbxj"/><path class="c_ir2fb_m"/><path fill="url(#i7QnpSd)" class="eahf9fbrk"/><path fill="url(#iJU4nte)" class="eahf9fbrk"/><path fill="url(#iBIuIbb)" class="j-tweow-u"/><path fill="url(#iC1kR7b)" class="j-tweow-u"/><path fill="url(#inq5wYb)" class="j-tweow-u"/><path fill="url(#iOthvwe)" class="j-tweow-u"/><path fill="url(#iuP6NMd)" class="bm7w23b9t"/><path fill="url(#iDv7Hjb)" class="bm7w23b9t"/><g filter="url(#iXVQjec)"><path class="y29qm1cbe"/><path fill="url(#iqiBu3b)" class="r7kas8b0r"/><path fill="url(#i7dsj4d)" class="r7kas8b0r"/></g><g filter="url(#inVx8Pb)"><path class="p8jkqmbdr"/><path fill="url(#iC9hKZc)" class="r7kas8b0r"/><path fill="url(#iiNRutc)" class="r7kas8b0r"/></g><path fill="url(#iWreuwe)" class="r7kas8b0r"/><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iq8HECb)" class="z30kudb-o"/><g filter="url(#iCfdyne)"><path class="fkflyvb_m"/><path fill="url(#iVm2pab)" class="uu9c01xwt"/><path fill="url(#iwXGa9c)" class="uu9c01xwt"/></g><g filter="url(#iZOWI8c)"><path class="ze31rdbyh"/></g><g filter="url(#isxv74q)"><path class="tdcimfbag"/><path fill="url(#iiReXXb)" class="h2pt4jb3o"/><path fill="url(#iggPa7b)" class="h2pt4jb3o"/></g><g filter="url(#i4ocSGb)"><path class="zt9dwabzu"/></g><path fill="url(#iWroyTd)" class="nrezcp5le"/><path fill="url(#izNTKdc)" class="nrezcp5le"/><path fill="url(#iiD6wCc)" class="nrezcp5le"/><path fill="url(#iKByDMe)" class="nrezcp5le"/><path fill="url(#iBJnkMe)" class="nrezcp5le"/><path fill="url(#i0GH0re)" class="b6pcaeboe"/><g filter="url(#iNoJQGd)"><path class="zepkmwb6a"/><path fill="url(#iaToRcc)" class="uw9pt0beg"/><path fill="url(#i4dfdjc)" class="uw9pt0beg"/><path fill="url(#ihLxlKX)" class="uw9pt0beg"/></g><g filter="url(#irIrQsc)"><path stroke="url(#it7BMRc)" class="iqsdfibon"/></g><path fill="url(#irGgnec)" class="f28zyusup"/><path fill="url(#iHeluSb)" class="ju-3ieb_x"/><g filter="url(#iE2UtFe)"><path fill="url(#itr4gqe)" class="qztwdpb3a"/></g><g filter="url(#i6EXflb)"><path fill="url(#ik0oY9d)" class="xtd36kb4i"/><path fill="url(#ipf12Vd)" class="xtd36kb4i"/></g><g filter="url(#ingxIVd)"><path class="t1kj7dzfh"/><path fill="url(#iCSDubd)" class="smjnbhbvi"/></g><g filter="url(#iLqgVgc)"><path class="h1unh-bmk"/><path fill="url(#i1qbwVd)" class="siiq3nrro"/></g><g filter="url(#ixaOZSd)"><path fill="url(#imZhIwM)" class="j_egekh3e"/><path fill="url(#iSc9Uxd)" class="j_egekh3e"/><path fill="url(#i0Jveeb)" class="j_egekh3e"/><path fill="url(#iFNjNEb)" class="j_egekh3e"/><path fill="url(#iEUEY5Y)" class="j_egekh3e"/><path fill="url(#idwTSbc)" class="j_egekh3e"/><path fill="url(#iImKgPd)" class="j_egekh3e"/></g><path fill="url(#iGwCoVa)" class="j_egekh3e"/><path fill="url(#is72Xxe)" class="j_egekh3e"/><g filter="url(#iUvTANe)"><path class="fw2_-t0bn"/></g><g filter="url(#iOhqyfd)"><path class="iuh9u4myv"/><path fill="url(#i9gecnA)" class="s2g0spbjn"/><path fill="url(#iKL63BJ)" class="s2g0spbjn"/><path fill="url(#itGjdBd)" class="s2g0spbjn"/><path fill="url(#ijEw1He)" class="s2g0spbjn"/></g><g filter="url(#iv5nYQF)"><path stroke="url(#iyOmyPd)" class="g1eviw0jb"/></g><path class="yfpiobkot"/><g filter="url(#imMdVvb)"><path class="hthl_vbvj"/></g><g filter="url(#i1Oelad)"><path class="b1zb943cj"/></g><g filter="url(#itWL2Od)"><path class="q-62skb2g"/></g><g filter="url(#i1nD3ad)"><path clip-rule="evenodd" class="mft3xnx1z"/></g><path class="i7yc29b2d"/><path fill="url(#iF4EBkc)" class="p9tooe6ij"/><path class="u94e10bxv"/><g filter="url(#ihI2yLc)"><path class="suy4z3unj"/><path fill="url(#ivpwyje)" class="if9fnsu_h"/></g><g filter="url(#ioGTqQe)"><path fill="url(#iRfVzAc)" class="aw0ls2bkc"/></g><path class="ljnflrbpp"/><path fill="url(#im2NTVn)" class="vmydf3bmt"/><path class="n_-vi4box"/><g filter="url(#izTE8Db)"><path fill="url(#iS6Ysvj)" class="zvyzwdb4v"/></g><g filter="url(#i6FONId)"><ellipse transform="rotate(-27.914 14.942 7.51)" class="vuphyxbyw"/><ellipse fill="url(#i5V9DqX)" transform="rotate(-27.914 14.942 7.51)" class="sb1sl3bfe"/></g><g filter="url(#ikXvv9b)"><path class="fppqjcbae"/><path fill="url(#iax6Fvb)" class="ode1fjv3z"/><path fill="url(#i8V6Apc)" class="ode1fjv3z"/></g><g filter="url(#iCEx21t)"><path class="kob1una5q"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="iwm4Qhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2671 2.01815 -2.52108 -.33365 15.894 8.923)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ifK6P7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27621 .86069 -1.13087 -1.67684 14.648 9.042)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i3F8fyb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.987 7.388)scale(.95273 .73156)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i2YtAnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57132 .93487 -.65853 -.40244 14.085 7.017)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iWKwshe" cx="0" cy="0" r="1" gradientTransform="matrix(.60841 1.15747 -1.60674 .84457 14.47 4.249)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ix4KcxJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.63805 .6381 -.89173 -.89167 18.61 5.169)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iQeDd9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.81612 .23743 -.49514 -1.70197 19.352 7.44)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="icWnIyo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24646 .31163 -.39697 -1.5878 19.085 8.953)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i4HKNQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40036 -1.17318 .92792 -.31667 18.123 6.362)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iZGqxTd" cx="0" cy="0" r="1" gradientTransform="matrix(.66573 .06978 -.11307 1.0787 13.3 7.419)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="ipQ5Pnc" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.217 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="inq5wYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.7132 -.85217 -.06096 15.406 25.564)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="cw-i9xbem"/><stop offset="1" class="t2qxtb2ul"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="i7dsj4d" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.2133 -.98624 .20888 19.32 18.972)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="s-dztxv8u"/><stop offset="1" class="wm2hnkwbm"/></radialGradient><radialGradient id="iiNRutc" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.2133 -.98624 .20888 19.32 18.972)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="wibfg_jba"/><stop offset="1" class="kgna9sqpj"/></radialGradient><radialGradient id="iWreuwe" cx="0" cy="0" r="1" gradientTransform="matrix(.71094 .42629 -1.32724 2.2135 16.606 22.867)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="s3qcrxbjw"/><stop offset="1" class="alg5_vbml"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iq8HECb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="aii5rr2eq"/><stop offset="1" class="yv8187b0r"/></radialGradient><radialGradient id="iVm2pab" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.875 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="z1su76bfy"/><stop offset="1" class="ykkax8bmp"/></radialGradient><radialGradient id="iwXGa9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 13.469)" gradientUnits="userSpaceOnUse"><stop class="p8zhg8wps"/><stop offset="1" class="is_m6u3tw"/></radialGradient><radialGradient id="iiReXXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="tdjl0hblu"/><stop offset="1" class="sb1zj3bbu"/></radialGradient><radialGradient id="iggPa7b" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="ywqn4-bmn"/><stop offset="1" class="njax42eii"/></radialGradient><radialGradient id="iiD6wCc" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1.0625 -3.8587 .39722 15.607 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="g7dj32byf"/><stop offset="1" class="mv_j9hb5m"/></radialGradient><radialGradient id="i0GH0re" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 1.25508 -2.35578 1.02647 15.148 10.137)" gradientUnits="userSpaceOnUse"><stop class="nov_osbjm"/><stop offset="1" class="b13j0jria"/></radialGradient><radialGradient id="ik0oY9d" cx="0" cy="0" r="1" gradientTransform="matrix(.80874 -.90149 1.10068 .98744 18.024 8.248)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ipf12Vd" cx="0" cy="0" r="1" gradientTransform="matrix(.58244 .32648 -.0923 .16467 18.273 7.072)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iCSDubd" cx="0" cy="0" r="1" gradientTransform="matrix(.66838 -.04967 .03883 .52249 17.955 7.857)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i1qbwVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.53421 0 0 -.42143 13.992 7.816)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="imZhIwM" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.815 5.687)scale(3.17026 4.24334)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iSc9Uxd" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 8.468 4.657)scale(1.5451 1.70551)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i0Jveeb" cx="0" cy="0" r="1" gradientTransform="matrix(.57873 -1.67684 2.1276 .7343 14.976 10.823)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iFNjNEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.97678 -3.44573 0 16.028 7.482)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="iEUEY5Y" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.01 4.99)scale(3.11521 5.36343)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="idwTSbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5094 .62518 0 17.047 7.393)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iImKgPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.581 .66587 0 15.11 7.292)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iGwCoVa" cx="0" cy="0" r="1" gradientTransform="matrix(-.56895 0 0 -2.85323 18.284 8.052)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="is72Xxe" cx="0" cy="0" r="1" gradientTransform="matrix(.581 1.77067 -3.0847 1.01217 15.061 4.923)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="i9gecnA" cx="0" cy="0" r="1" gradientTransform="matrix(-.20165 -.90481 .27886 -.06215 16.375 8.373)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ijEw1He" cx="0" cy="0" r="1" gradientTransform="matrix(-.34501 0 0 -.09646 16.27 8.467)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iF4EBkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35914 -.57125 0 16.994 7.552)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ivpwyje" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 10.305 -.342)scale(.16745 .23055)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im2NTVn" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35914 -.57126 0 15.062 7.552)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i5V9DqX" cx="0" cy="0" r="1" gradientTransform="matrix(-.00342 -.2187 .26289 -.00412 14.935 7.65)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iax6Fvb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.083 7.459)scale(2.15707 3.52668)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i8V6Apc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0931 .60521 -1.30208 -.20032 16.121 4.472)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iAy6hEE" width="7.335" height="7.371" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1157" result="effect2_innerShadow_4002_1157"/></filter><filter id="iNR2fXu" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1157" result="effect2_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1157" result="effect3_innerShadow_4002_1157"/></filter><filter id="imGabCe" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1157" result="effect2_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1157" result="effect3_innerShadow_4002_1157"/></filter><filter id="i4lLjJs" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="i582jjc" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1157" result="effect2_dropShadow_4002_1157"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1157" result="shape"/></filter><filter id="icEILcd" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1157" result="effect2_dropShadow_4002_1157"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1157" result="shape"/></filter><filter id="iJ3eXbc" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1157" result="effect2_dropShadow_4002_1157"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1157" result="shape"/></filter><filter id="iaeF3gc" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1157" result="effect2_dropShadow_4002_1157"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1157" result="shape"/></filter><filter id="iLBdh0d" width="6.898" height="7.398" x="12.704" y="3.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="ieUKStc" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="i8y9yrc" width="4.084" height="3.799" x="20.732" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="iXVQjec" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="inVx8Pb" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.631373 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="iCfdyne" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.576471 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.470588 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1157" result="effect2_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.67451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1157" result="effect3_innerShadow_4002_1157"/></filter><filter id="iZOWI8c" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="isxv74q" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.54902 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="i4ocSGb" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.517647 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="iNoJQGd" width="6.349" height="5.065" x="13.14" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.415686 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1157" result="effect2_innerShadow_4002_1157"/></filter><filter id="irIrQsc" width="4.609" height="5.161" x="18.951" y="9.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".25"/></filter><filter id="iE2UtFe" width="1.575" height="1.425" x="13.242" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="i6EXflb" width="1.425" height="1.675" x="17.453" y="6.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="ingxIVd" width="1.351" height="1.351" x="17.49" y="7.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".1"/></filter><filter id="iLqgVgc" width="1.751" height="1.751" x="13.087" y="6.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".2"/></filter><filter id="ixaOZSd" width="4.511" height="5.215" x="13.773" y="5.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="iUvTANe" width="1.831" height="2.187" x="15.041" y="7.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".25"/></filter><filter id="iOhqyfd" width="1.031" height="1.387" x="15.513" y="7.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".05"/></filter><filter id="iv5nYQF" width="1.762" height=".798" x="15.148" y="8.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".05"/></filter><filter id="imMdVvb" width="1.44" height=".569" x="16.334" y="7.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="i1Oelad" width="1.44" height=".569" x="14.283" y="7.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="itWL2Od" width="1.197" height=".594" x="14.342" y="6.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="i1nD3ad" width="1.197" height=".594" x="16.741" y="6.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/></filter><filter id="ihI2yLc" width=".46" height=".42" x="16.613" y="7.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".05"/></filter><filter id="ioGTqQe" width=".617" height=".627" x="16.93" y="7.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".1"/></filter><filter id="izTE8Db" width=".66" height=".683" x="14.963" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".1"/></filter><filter id="i6FONId" width=".516" height=".423" x="14.684" y="7.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".05"/></filter><filter id="ikXvv9b" width="4.038" height="2.638" x="14.458" y="4.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1157"/><feGaussianBlur result="effect2_foregroundBlur_4002_1157" stdDeviation=".05"/></filter><filter id="iCEx21t" width="2.781" height="1.429" x="15.803" y="5.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1157" stdDeviation=".15"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="itMYOMb" x1="18.106" x2="15.094" y1="4.739" y2="10.318" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iBIuIbb" x1="15.345" x2="13.875" y1="24.348" y2="24.348" gradientUnits="userSpaceOnUse"><stop offset=".267" class="bs-ywhjno"/><stop offset="1" class="zss1t2k2l"/></linearGradient><linearGradient id="iC1kR7b" x1="15.517" x2="15.017" y1="26.036" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="iwsb7zzqk"/><stop offset="1" class="ce0bg7b-n"/></linearGradient><linearGradient id="iOthvwe" x1="13.318" x2="13.75" y1="24.833" y2="24.833" gradientUnits="userSpaceOnUse"><stop class="tgkl8ebfm"/><stop offset="1" class="wvqlanbxz"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="iqiBu3b" x1="18.825" x2="18.304" y1="23.645" y2="23.388" gradientUnits="userSpaceOnUse"><stop class="rr5fu4pew"/><stop offset="1" class="u39dyibqi"/></linearGradient><linearGradient id="iC9hKZc" x1="18.825" x2="18.304" y1="23.645" y2="23.388" gradientUnits="userSpaceOnUse"><stop class="gqr8sybry"/><stop offset="1" class="lpb-gbbwk"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="iWroyTd" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="z9-ns_cqv"/><stop offset="1" class="voshhcbhx"/></linearGradient><linearGradient id="izNTKdc" x1="13.267" x2="15.139" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="w8z9c1bqk"/><stop offset="1" class="d1stbzbsu"/></linearGradient><linearGradient id="iKByDMe" x1="18.792" x2="16.607" y1="13.948" y2="13.948" gradientUnits="userSpaceOnUse"><stop class="eo1g38slj"/><stop offset="1" class="s89mq5-5f"/></linearGradient><linearGradient id="iBJnkMe" x1="18.96" x2="17.959" y1="14.225" y2="14.225" gradientUnits="userSpaceOnUse"><stop offset=".049" class="bpn-u35sy"/><stop offset="1" class="ukj380brt"/></linearGradient><linearGradient id="iaToRcc" x1="13.14" x2="15.351" y1="18.9" y2="18.9" gradientUnits="userSpaceOnUse"><stop class="c2g5jlmdp"/><stop offset="1" class="j9-ktqfbw"/></linearGradient><linearGradient id="i4dfdjc" x1="19.255" x2="16.729" y1="18.309" y2="18.9" gradientUnits="userSpaceOnUse"><stop offset=".349" class="hta3d8bay"/><stop offset="1" class="yezlp2beb"/></linearGradient><linearGradient id="ihLxlKX" x1="19.489" x2="18.607" y1="18.386" y2="18.614" gradientUnits="userSpaceOnUse"><stop class="wg5i7s-vd"/><stop offset="1" class="pql-90wca"/></linearGradient><linearGradient id="it7BMRc" x1="22.451" x2="19.857" y1="11.683" y2="13.527" gradientUnits="userSpaceOnUse"><stop offset=".453" class="yyuqaqb0l"/><stop offset="1" class="g_3g2umds"/></linearGradient><linearGradient id="irGgnec" x1="12.937" x2="19.259" y1="10.014" y2="10.014" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeluSb" x1="12.937" x2="19.259" y1="10.001" y2="10.001" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="itr4gqe" x1="13.242" x2="14.552" y1="7.855" y2="7.855" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iKL63BJ" x1="15.613" x2="16.028" y1="8.405" y2="8.405" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="itGjdBd" x1="16.028" x2="16.028" y1="8.759" y2="8.489" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iyOmyPd" x1="15.557" x2="15.761" y1="9.383" y2="9.068" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="iRfVzAc" x1="17.339" x2="17.2" y1="7.576" y2="7.661" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iS6Ysvj" x1="15.392" x2="15.253" y1="7.576" y2="7.661" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-fairy-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.aii5rr2eq {
  stop-color: var(--svg-color--eeb39e, #EEB39E);
}

.alg5_vbml {
  stop-color: var(--svg-color--e49d85, #E49D85);
  stop-opacity: 0;
}

.aw0ls2bkc {
  d: path("M17.347 7.684a.37.37 0 0 0-.102-.205l-.115.126l.052.101z");
}

.b13j0jria {
  stop-color: var(--svg-color--f4baae, #F4BAAE);
}

.b1zb943cj {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.523 7.564c-.118-.206-.296-.37-.68-.37a.73.73 0 0 0-.476.164c-.119.096-.103.219-.01.265l.246.14c.288-.093.607-.105.92-.199");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b6pcaeboe {
  d: path("M15.07 10.136v.699a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.699z");
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bm7w23b9t {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.bpn-u35sy {
  stop-color: var(--svg-color--9771bf, #9771BF);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bs-ywhjno {
  stop-color: var(--svg-color--ffd1bd, #FFD1BD);
}

.c_ir2fb_m {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.39v-.862h5.525v.82a49 49 0 0 1-5.525.042");
}

.c2g5jlmdp {
  stop-color: var(--svg-color--67568f, #67568F);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ce0bg7b-n {
  stop-color: var(--svg-color--f5b7a1, #F5B7A1);
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

.cw-i9xbem {
  stop-color: var(--svg-color--ba8d88, #BA8D88);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d1stbzbsu {
  stop-color: var(--svg-color--8664c8, #8664C8);
  stop-opacity: 0;
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dv6-6mbxj {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .129.376l-.735.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.319.237l-.864-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
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

.eahf9fbrk {
  d: path("M13.267 16.39v-.862h5.525v.82a49 49 0 0 1-5.525.042");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.eo1g38slj {
  stop-color: var(--svg-color--ac8de6, #AC8DE6);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.er079sbvz {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.668l-.84.085a.21.21 0 0 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f28zyusup {
  d: path("M16.253 10.001q.166.009.338.022c-.114-.008-.224-.017-.338-.022");
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fkflyvb_m {
  fill: var(--svg-color--f1bdad, #F1BDAD);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.fppqjcbae {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.761 4.367c-.501-.11-.951.39-1.003.575c.465 1.57 1.643 1.484 2.806 1.355c.696-.078.772.24.831.393c0-1.741-1.48-2.068-2.621-2.32z");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fw2_-t0bn {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.855 7.717l-.303.753a.24.24 0 0 0 .23.31h.349a.24.24 0 0 0 .23-.31l-.235-.753c-.05-.166-.219-.166-.271 0");
}

.g_3g2umds {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1eviw0jb {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.029 9.105a1.34 1.34 0 0 1-.63-.153c-.062-.032-.129.04-.09.098a.855.855 0 0 0 1.439 0c.039-.06-.028-.13-.09-.098a1.3 1.3 0 0 1-.63.153Z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7dj32byf {
  stop-color: var(--svg-color--402d65, #402D65);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gqr8sybry {
  stop-color: var(--svg-color--e9b9ad, #E9B9AD);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1unh-bmk {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M13.963 8.292a.475.475 0 1 0 0-.951a.475.475 0 0 0 0 .95");
}

.h2pt4jb3o {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hta3d8bay {
  stop-color: var(--svg-color--9882d5, #9882D5);
}

.hthl_vbvj {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.534 7.564c.117-.206.296-.37.68-.37a.73.73 0 0 1 .475.164c.12.096.103.219.011.265l-.246.14c-.288-.093-.608-.105-.92-.199");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i7yc29b2d {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.087 7.22c.289 0 .533.2.6.47c.02.076-.04.15-.12.15h-.987a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .607-.5");
}

.if9fnsu_h {
  d: path("M16.966 7.424c.028.038-.03.084-.098.134c-.066.05-.116.085-.144.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iqsdfibon {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.701 12.745l2.672 1.045a.1.1 0 0 0 .136-.084l.302-3.57");
}

.is_m6u3tw {
  stop-color: var(--svg-color--c36f72, #C36F72);
  stop-opacity: 0;
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.iuh9u4myv {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.859 7.656l-.235.753a.24.24 0 0 0 .23.31h.348a.24.24 0 0 0 .23-.31l-.234-.753c-.05-.166-.286-.166-.339 0");
}

.iwsb7zzqk {
  stop-color: var(--svg-color--f5b7a1, #F5B7A1);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j_egekh3e {
  d: path("M13.776 7.257h.006l-.005-.117l-.004-.136c.009-.42.254-.582.358-.636l.023-.01l.023-.009a1.02 1.02 0 0 0 .526-.546l.037-.086c.036-.086.15-.1.204-.022c.318.465.849.74 1.412.74h1.425c.08 0 .48.039.503.59l-.053 1.36c-.054 1.24-1.023 2.074-2.206 2.074c-1.182 0-2.151-.833-2.205-2.074z");
}

.j-tweow-u {
  d: path("M13.318 29.589v-9.484l2.32.062l-.495 8.676a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j9-ktqfbw {
  stop-color: var(--svg-color--8266c3, #8266C3);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.ju-3ieb_x {
  d: path("M16.108 10.001h-.018q.064-.001.128.005q-.056-.006-.11-.005");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kgna9sqpj {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
  stop-opacity: 0;
}

.kob1una5q {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.094 5.965l-.632.116a.305.305 0 1 1-.055-.604h1.036c.613 0 .816.618.84.829a1.4 1.4 0 0 0-1.19-.34");
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
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

.ljnflrbpp {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.97 7.22c-.29 0-.533.2-.6.47c-.02.076.04.15.119.15h.987a.102.102 0 0 0 .101-.12a.62.62 0 0 0-.607-.5");
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lpb-gbbwk {
  stop-color: var(--svg-color--e9b9ad, #E9B9AD);
  stop-opacity: 0;
}

.m8pucsqyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.668l.84.085a.21.21 0 0 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mft3xnx1z {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m17.68 6.827l-.061.101za.119.119 0 0 1-.122.203h-.002l-.01-.006l-.04-.02a1 1 0 0 0-.152-.06a1 1 0 0 0-.474-.041a.119.119 0 0 1-.041-.234c.227-.04.437 0 .588.048a1.5 1.5 0 0 1 .247.106l.004.002z");
}

.mv_j9hb5m {
  stop-color: var(--svg-color--634990, #634990);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n_-vi4box {
  fill: var(--svg-color--000, #000);
  d: path("M15.288 7.736c0-.126-.1-.227-.226-.227a.225.225 0 0 0-.202.33h.4a.2.2 0 0 0 .028-.103");
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.njax42eii {
  stop-color: var(--svg-color--f1bdad, #F1BDAD);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nov_osbjm {
  stop-color: var(--svg-color--e19d8a, #E19D8A);
}

.nrezcp5le {
  d: path("M16.017 10.709c-.438.015-1.42.084-1.985.163c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a25 25 0 0 0-1.985-.163z");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ode1fjv3z {
  d: path("M15.761 4.367c-.501-.11-.951.39-1.003.575c.465 1.57 1.643 1.484 2.806 1.355c.696-.078.772.24.831.393c0-1.741-1.48-2.068-2.621-2.32z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p8jkqmbdr {
  fill: var(--svg-color--fbc5b5, #FBC5B5);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.p8zhg8wps {
  stop-color: var(--svg-color--c36f72, #C36F72);
}

.p9tooe6ij {
  d: path("M16.995 7.34a.395.395 0 0 1 .38.5h-.762a.397.397 0 0 1 .382-.5");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pql-90wca {
  stop-color: var(--svg-color--9f8cca, #9F8CCA);
  stop-opacity: 0;
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.q-62skb2g {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M14.524 7.03h-.002a.119.119 0 0 1-.122-.203l.002-.002l.004-.002l.015-.008l.051-.026c.044-.02.106-.047.182-.072c.15-.048.36-.088.588-.048a.119.119 0 1 1-.042.234c-.176-.031-.346 0-.474.04a1 1 0 0 0-.192.08z");
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
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

.qztwdpb3a {
  d: path("M13.954 8.528a.712.712 0 1 0 0-1.424a.712.712 0 0 0 0 1.424");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r7kas8b0r {
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rr5fu4pew {
  stop-color: var(--svg-color--dba697, #DBA697);
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s-dztxv8u {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s2g0spbjn {
  d: path("m15.859 7.656l-.235.753a.24.24 0 0 0 .23.31h.348a.24.24 0 0 0 .23-.31l-.234-.753c-.05-.166-.286-.166-.339 0");
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s3qcrxbjw {
  stop-color: var(--svg-color--d3947d, #D3947D);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s89mq5-5f {
  stop-color: var(--svg-color--9673d5, #9673D5);
  stop-opacity: 0;
}

.sb1sl3bfe {
  cx: 14.942px;
  cy: 7.51px;
  rx: 0.172px;
  ry: 0.087px;
}

.sb1zj3bbu {
  stop-color: var(--svg-color--fccbb7, #FCCBB7);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.siiq3nrro {
  d: path("M13.963 8.292a.475.475 0 1 0 0-.951a.475.475 0 0 0 0 .95");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.smjnbhbvi {
  d: path("M18.165 8.292a.475.475 0 1 0 0-.951a.475.475 0 0 0 0 .95");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suy4z3unj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.966 7.424c.028.038-.03.084-.098.134c-.066.05-.116.085-.144.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t1kj7dzfh {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M18.165 8.292a.475.475 0 1 0 0-.951a.475.475 0 0 0 0 .95");
}

.t2qxtb2ul {
  stop-color: var(--svg-color--e5af9f, #E5AF9F);
  stop-opacity: 0;
}

.tdcimfbag {
  fill: var(--svg-color--eab8a0, #EAB8A0);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tdjl0hblu {
  stop-color: var(--svg-color--fccbb7, #FCCBB7);
}

.tgkl8ebfm {
  stop-color: var(--svg-color--f1b69f, #F1B69F);
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tt1u2qbmw {
  fill-rule: evenodd;
  d: path("M19.209 8.44a1.45 1.45 0 0 0 .024-1.21h.003a1.4 1.4 0 0 0-.125-.226v-.002a1.43 1.43 0 0 1-.233-.784v-.004a1.46 1.46 0 0 0-1.46-1.46a.24.24 0 0 1-.203-.104a1.463 1.463 0 0 0-2.374 0a.25.25 0 0 1-.201.103h-.038a1.46 1.46 0 0 0-1.423 1.46v.005c0 .278-.08.551-.233.784v.002a1.46 1.46 0 0 0-.098 1.436a.23.23 0 0 1 0 .202a1.422 1.422 0 0 0 1.281 2.047h3.799a1.422 1.422 0 0 0 1.281-2.047a.23.23 0 0 1 0-.202m-5.427-1.183h-.006l.531 1.043c.055 1.24.539 0 1.721 0c1.183 0 1.699 1.38 1.753.14l.503-1.415c-.024-.551-.423-.59-.503-.59h-1.425a1.71 1.71 0 0 1-1.412-.74a.117.117 0 0 0-.204.022l-.037.086a1.02 1.02 0 0 1-.549.555l-.023.01c-.104.054-.35.216-.358.636l.004.136z");
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u39dyibqi {
  stop-color: var(--svg-color--dba697, #DBA697);
  stop-opacity: 0;
}

.u94e10bxv {
  fill: var(--svg-color--000, #000);
  d: path("M16.769 7.736c0-.126.1-.227.226-.227a.225.225 0 0 1 .201.33h-.4a.2.2 0 0 1-.027-.103");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ukj380brt {
  stop-color: var(--svg-color--a585e1, #A585E1);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uu9c01xwt {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.uw9pt0beg {
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
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

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vmydf3bmt {
  d: path("M15.061 7.34a.395.395 0 0 0-.38.5h.763a.398.398 0 0 0-.383-.5");
}

.voshhcbhx {
  stop-color: var(--svg-color--8466c6, #8466C6);
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vsr9738qr {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.vuphyxbyw {
  cx: 14.942px;
  cy: 7.51px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w8z9c1bqk {
  stop-color: var(--svg-color--6f5187, #6F5187);
}

.wg5i7s-vd {
  stop-color: var(--svg-color--8569c7, #8569C7);
}

.wibfg_jba {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wm2hnkwbm {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
  stop-opacity: 0;
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wvqlanbxz {
  stop-color: var(--svg-color--f1b69f, #F1B69F);
  stop-opacity: 0;
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xtd36kb4i {
  d: path("M18.165 8.528a.712.712 0 1 0 0-1.424a.712.712 0 0 0 0 1.424");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y29qm1cbe {
  fill: var(--svg-color--e7ae99, #E7AE99);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.yezlp2beb {
  stop-color: var(--svg-color--8467c6, #8467C6);
  stop-opacity: 0;
}

.yfpiobkot {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.029 9.105a1.34 1.34 0 0 1-.63-.153c-.062-.032-.129.04-.09.098a.855.855 0 0 0 1.439 0c.039-.06-.028-.13-.09-.098a1.3 1.3 0 0 1-.63.153");
}

.ykkax8bmp {
  stop-color: var(--svg-color--d3a086, #D3A086);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yv8187b0r {
  stop-color: var(--svg-color--c38488, #C38488);
}

.ywqn4-bmn {
  stop-color: var(--svg-color--f1bdad, #F1BDAD);
  stop-opacity: 0;
}

.yyuqaqb0l {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z1su76bfy {
  stop-color: var(--svg-color--d3a086, #D3A086);
  stop-opacity: 0;
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z9-ns_cqv {
  stop-color: var(--svg-color--916ed5, #916ED5);
}

.ze31rdbyh {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.zepkmwb6a {
  fill: var(--svg-color--8569c7, #8569C7);
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zss1t2k2l {
  stop-color: var(--svg-color--ebb3a3, #EBB3A3);
}

.zt9dwabzu {
  fill: var(--svg-color--f2b7a1, #F2B7A1);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0V8.51a.404.404 0 0 0-.805-.035c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.zvyzwdb4v {
  d: path("M15.422 7.69c0-.128-.103-.213-.132-.24l-.127.124l.078.16z");
}

</style>
