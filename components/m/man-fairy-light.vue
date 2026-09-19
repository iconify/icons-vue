<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixA2Pne)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#i8ENfKb)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iCJKZIQ)"><path fill="url(#i5I72Pc)" class="pb1pwib-r"/><path fill="url(#iX1BTZW)" class="pb1pwib-r"/></g><g filter="url(#i2hUq1d)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#ilouE6d)"><path class="t6m6gnbiw"/></g><g filter="url(#ieRvQvb)"><path class="yn_cprukr"/></g><g filter="url(#ipKeqbd)"><path class="y3su9tbbh"/></g><g filter="url(#i3ZzLjc)"><path class="a48brs4te"/></g><g filter="url(#iwxkwwe)"><rect class="r9m8_svvg"/><rect fill="url(#iVtR9se)" class="nl4f7twra"/></g><g filter="url(#ip0zVGb)"><path fill="url(#ioitlCc)" class="t16p7zajb"/></g><path fill="url(#i5Ao9Gd)" class="t16p7zajb"/><path fill="url(#i8KfH3d)" class="t16p7zajb"/><path fill="url(#iEdEbnd)" class="t16p7zajb"/><path class="ls3dj269w"/><path fill="url(#iGgZmQl)" class="usyhe_b6f"/><path fill="url(#iVakvLc)" class="usyhe_b6f"/><path fill="url(#i3gy0Bb)" class="usyhe_b6f"/><path fill="url(#iuPT4Kc)" class="usyhe_b6f"/><path fill="url(#iHyYx2b)" class="usyhe_b6f"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><path fill="url(#iHwKGuc)" class="fwk98bb0c"/><path fill="url(#iG2idHc)" class="fwk98bb0c"/><path fill="url(#i3NKrre)" class="fwk98bb0c"/><path fill="url(#i7mB2nb)" class="fwk98bb0c"/><path fill="url(#iR15onA)" class="hxm_1sbuv"/><path fill="url(#iDv7Hjb)" class="hxm_1sbuv"/><g filter="url(#i4qlLIe)"><path class="no129_bju"/><path fill="url(#iIEs1Hd)" class="ajsjeuojy"/><path fill="url(#iowaBtV)" class="ajsjeuojy"/></g><path fill="url(#iqaK8tc)" class="ajsjeuojy"/><path fill="url(#iFc3g8a)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iq8HECb)" class="z30kudb-o"/><g filter="url(#ikTUSke)"><path class="fkflyvb_m"/><path fill="url(#irAmuSc)" class="uu9c01xwt"/><path fill="url(#iwXGa9c)" class="uu9c01xwt"/></g><g filter="url(#ibC3PEL)"><path class="p3xpydy4e"/><path fill="url(#iiReXXb)" class="re9d71n0d"/><path fill="url(#iggPa7b)" class="re9d71n0d"/></g><g filter="url(#iArrWPd)"><path class="nb-v65buu"/></g><path fill="url(#i8i03nb)" class="ek-1fff6o"/><path fill="url(#ilgpd4F)" class="ek-1fff6o"/><path fill="url(#i3NK0Ud)" class="ek-1fff6o"/><path fill="url(#iLUZ8fb)" class="ek-1fff6o"/><path fill="url(#iWi8cUd)" class="ek-1fff6o"/><path fill="url(#iRJZlyc)" class="ek-1fff6o"/><path fill="url(#iDDLGOd)" class="ek-1fff6o"/><path fill="url(#ibNXoTc)" class="gdfj27b8p"/><g filter="url(#ihb3vUW)"><path stroke="url(#i9tL5Vd)" class="saunobcmg"/></g><g filter="url(#inAMFFe)"><path stroke="url(#in0SVNc)" class="ikgkim2qs"/></g><g filter="url(#ioR33Ks)"><path stroke="url(#iXQsZLe)" class="zh46g387g"/></g><g filter="url(#iDTiLPb)"><circle fill="url(#iW6ylPY)" class="d2gfipb4k"/></g><g filter="url(#iAxhpge)"><circle fill="url(#ig9WlCc)" class="z75qbob3v"/></g><g filter="url(#iOFeuge)"><circle fill="url(#iXMCn2b)" class="t142bdb_h"/><circle fill="url(#iBCwNJP)" class="t142bdb_h"/></g><g filter="url(#il7m5Sd)"><circle class="j4lcbbc1h"/><circle fill="url(#ibemRTc)" class="a2by3czaa"/><circle fill="url(#ia1Vo9b)" class="a2by3czaa"/></g><g filter="url(#iIKG2Hc)"><path fill="url(#isgqYIc)" class="q9tdvibpa"/><path fill="url(#iCIFVdb)" class="q9tdvibpa"/><path fill="url(#i6GuzMe)" class="q9tdvibpa"/><path fill="url(#iekUSVc)" class="q9tdvibpa"/><path fill="url(#ihJ9S0M)" class="q9tdvibpa"/><path fill="url(#ivtMiPb)" class="q9tdvibpa"/></g><g filter="url(#iJgiUse)"><path fill="url(#ivwITCu)" class="k_-pp4tvx"/></g><g filter="url(#inTJTUb)"><path class="s8ovo2bbk"/><path fill="url(#ikUfPJb)" class="d67-4i_lm"/><path fill="url(#ifDy2bv)" class="d67-4i_lm"/><path fill="url(#iAhCm0c)" class="d67-4i_lm"/><path fill="url(#iFBxuVc)" class="d67-4i_lm"/></g><g filter="url(#iuk3Ubb)"><path class="greotackh"/></g><g filter="url(#iWUHf6d)"><path class="w-1p8nn-n"/><path fill="url(#iSvpdbb)" class="wh5hl9ggo"/><path fill="url(#iIC4mPL)" class="wh5hl9ggo"/><path fill="url(#i4GLinY)" class="wh5hl9ggo"/><path fill="url(#ifOFUKM)" class="wh5hl9ggo"/></g><path class="b68_6u4-q"/><g filter="url(#iWsb3Pd)"><path class="h0miccc8s"/></g><g filter="url(#i9YlwOb)"><path class="x3rydqk_a"/></g><path class="muudq6bym"/><path fill="url(#imG1znM)" class="y0ghjsngh"/><path class="qqdmv7_7m"/><g filter="url(#iV4Cryc)"><path class="urtx-5blf"/><path fill="url(#ixrCECb)" class="yvzenumps"/></g><g filter="url(#iu5CC4b)"><path fill="url(#i6iWrbb)" class="itfpqxb5a"/></g><path class="v1jna4b3w"/><path fill="url(#iQyaMne)" class="au9xqqdjp"/><path class="tzpzpobmp"/><g filter="url(#iY2oqvH)"><path fill="url(#irKophD)" class="tv4w4-j7e"/></g><g filter="url(#iTMvFXd)"><ellipse transform="rotate(-27.914 14.961 7.594)" class="wwuyjbert"/><ellipse fill="url(#i6JlyJc)" transform="rotate(-27.914 14.961 7.594)" class="y-5m-ibgn"/></g><g filter="url(#iSyfQvc)"><path stroke="url(#ibJWFGe)" class="ikgiddbts"/></g><g filter="url(#i1i60Le)"><path stroke="url(#iTWhwYc)" class="pl0mjl3nz"/></g><g filter="url(#iyccSPb)"><path stroke="url(#iZRjS7d)" class="ep2-myb1w"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iVakvLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68754 -5.0625 2.53124 -.34377 16.78 21.98)" gradientUnits="userSpaceOnUse"><stop class="uvyxh01-z"/><stop offset="1" class="u2p7zvbzn"/></radialGradient><radialGradient id="i3gy0Bb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.125 15.9 2.484)scale(.88884 .66004)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="kcor2lvvo"/><stop offset="1" class="t0dfidbsh"/></radialGradient><radialGradient id="iHyYx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 -4.56052 .72812 .03493 14.75 21.79)" gradientUnits="userSpaceOnUse"><stop class="ywk-_ln5y"/><stop offset="1" class="quxai4aum"/></radialGradient><radialGradient id="i3NKrre" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.09375 -.85026 -.073 15.348 26.277)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="cw-i9xbem"/><stop offset="1" class="t2qxtb2ul"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iowaBtV" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="wibfg_jba"/><stop offset="1" class="kgna9sqpj"/></radialGradient><radialGradient id="iqaK8tc" cx="0" cy="0" r="1" gradientTransform="matrix(.71094 .34759 -.96823 1.98037 16.606 23.744)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="s3qcrxbjw"/><stop offset="1" class="alg5_vbml"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iq8HECb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="aii5rr2eq"/><stop offset="1" class="yv8187b0r"/></radialGradient><radialGradient id="irAmuSc" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.875 -1.302)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="z1su76bfy"/><stop offset="1" class="ykkax8bmp"/></radialGradient><radialGradient id="iwXGa9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 13.469)" gradientUnits="userSpaceOnUse"><stop class="p8zhg8wps"/><stop offset="1" class="is_m6u3tw"/></radialGradient><radialGradient id="iiReXXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="tdjl0hblu"/><stop offset="1" class="sb1zj3bbu"/></radialGradient><radialGradient id="iggPa7b" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="ywqn4-bmn"/><stop offset="1" class="njax42eii"/></radialGradient><radialGradient id="i3NK0Ud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.194 10.724)" gradientUnits="userSpaceOnUse"><stop class="ptfvfcbrt"/><stop offset="1" class="c9v8_hpvm"/></radialGradient><radialGradient id="iLUZ8fb" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.144 8.855)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="y39x50mqx"/><stop offset="1" class="gmn2w47zp"/></radialGradient><radialGradient id="iWi8cUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.67188 0 0 .4274 16.843 10.724)" gradientUnits="userSpaceOnUse"><stop class="nkm4r8_8f"/><stop offset="1" class="e2kf81bwk"/></radialGradient><radialGradient id="ibNXoTc" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="nov_osbjm"/><stop offset="1" class="b13j0jria"/></radialGradient><radialGradient id="iW6ylPY" cx="0" cy="0" r="1" gradientTransform="matrix(.76321 0 0 1.33563 13.238 7.932)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iBCwNJP" cx="0" cy="0" r="1" gradientTransform="matrix(.35954 -.2618 .29881 .41037 18.263 7.817)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ibemRTc" cx="0" cy="0" r="1" gradientTransform="matrix(.35718 -.65695 .38451 .20906 18.084 8.29)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ia1Vo9b" cx="0" cy="0" r="1" gradientTransform="matrix(.11277 .11162 -.1439 .14537 18.102 7.932)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iCIFVdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.10351 -5.5703 0 16.042 7.095)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="ihJ9S0M" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56846 .69965 0 17.05 7.38)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="ivtMiPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6049 .75225 0 15.067 7.365)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ikUfPJb" cx="0" cy="0" r="1" gradientTransform="matrix(.34698 -1.28587 .47684 .12867 17.919 6.146)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ifDy2bv" cx="0" cy="0" r="1" gradientTransform="matrix(1.66346 .15308 -.08231 .89443 17.204 5.381)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iAhCm0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7303 -1.13102 0 16.029 4.191)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iFBxuVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3369 -.9797 1.53488 2.09448 13.224 7.157)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="ifOFUKM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08563 -.27512 0 16.171 8.631)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="imG1znM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35277 -.56112 0 16.977 7.636)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ixrCECb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10084 -.12995 .1789 -.13883 16.877 7.672)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQyaMne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35279 -.56115 0 15.079 7.636)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6JlyJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21483 .25824 -.00404 14.954 7.731)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ixA2Pne" width="7.335" height="7.371" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1158" result="effect2_innerShadow_4002_1158"/></filter><filter id="i8ENfKb" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1158" result="effect2_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1158" result="effect3_innerShadow_4002_1158"/></filter><filter id="iCJKZIQ" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1158" result="effect2_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1158" result="effect3_innerShadow_4002_1158"/></filter><filter id="i2hUq1d" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="ilouE6d" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1158" result="effect2_dropShadow_4002_1158"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1158" result="shape"/></filter><filter id="ieRvQvb" width="6.45" height="6.548" x="9.619" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1158" result="effect2_dropShadow_4002_1158"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1158" result="shape"/></filter><filter id="ipKeqbd" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1158" result="effect2_dropShadow_4002_1158"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1158" result="shape"/></filter><filter id="i3ZzLjc" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1158" result="effect2_dropShadow_4002_1158"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1158" result="shape"/></filter><filter id="iwxkwwe" width="1.003" height="4.833" x="22.341" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="ip0zVGb" width="4.084" height="3.799" x="20.732" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="i4qlLIe" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.631373 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="ikTUSke" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.576471 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.470588 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1158" result="effect2_innerShadow_4002_1158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.67451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1158" result="effect3_innerShadow_4002_1158"/></filter><filter id="ibC3PEL" width="1.692" height="1.561" x="6.723" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.54902 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="iArrWPd" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.517647 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="ihb3vUW" width="4.609" height="5.161" x="19.13" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".25"/></filter><filter id="inAMFFe" width="1.248" height="2.077" x="21.759" y="8.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".1"/></filter><filter id="ioR33Ks" width=".822" height="1.445" x="22.798" y="8.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".1"/></filter><filter id="iDTiLPb" width="1.652" height="1.452" x="13.238" y="7.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="iAxhpge" width="1.865" height="1.865" x="13.031" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".25"/></filter><filter id="iOFeuge" width="1.702" height="1.702" x="17.375" y="6.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="il7m5Sd" width="1.865" height="1.865" x="17.169" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".25"/></filter><filter id="iIKG2Hc" width="4.512" height="5.481" x="13.786" y="5.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="iJgiUse" width="3.847" height="3.334" x="15.103" y="4.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".5"/></filter><filter id="inTJTUb" width="5.481" height="3.598" x="13.289" y="4.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="iuk3Ubb" width="2.265" height="2.666" x="14.792" y="7.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".375"/></filter><filter id="iWUHf6d" width="1.016" height="1.366" x="15.521" y="7.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".05"/></filter><filter id="iWsb3Pd" width="1.437" height="1.041" x="16.543" y="6.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="i9YlwOb" width="1.437" height="1.041" x="14.304" y="6.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1158"/></filter><filter id="iV4Cryc" width=".455" height=".416" x="16.601" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".05"/></filter><filter id="iu5CC4b" width=".614" height=".623" x="16.91" y="7.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".1"/></filter><filter id="iY2oqvH" width=".655" height=".678" x="14.978" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".1"/></filter><filter id="iTMvFXd" width=".51" height=".419" x="14.706" y="7.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".05"/></filter><filter id="iSyfQvc" width="1.254" height=".638" x="16.526" y="6.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".075"/></filter><filter id="i1i60Le" width="1.288" height=".662" x="14.256" y="6.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".075"/></filter><filter id="iyccSPb" width=".862" height="1.411" x="13.57" y="5.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1158" stdDeviation=".125"/></filter><linearGradient id="i5I72Pc" x1="8.528" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iVtR9se" x1="22.919" x2="22.549" y1="5.345" y2="6.132" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="iGgZmQl" x1="13.264" x2="15.031" y1="19.026" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="i7ccoc8qs"/><stop offset="1" class="waah2bcle"/></linearGradient><linearGradient id="iuPT4Kc" x1="19.343" x2="17.937" y1="18.573" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="hnwux9dcc"/><stop offset="1" class="xsno6rw2t"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iHwKGuc" x1="15.288" x2="13.817" y1="25.263" y2="25.263" gradientUnits="userSpaceOnUse"><stop offset=".267" class="bs-ywhjno"/><stop offset="1" class="zss1t2k2l"/></linearGradient><linearGradient id="iG2idHc" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="iwsb7zzqk"/><stop offset="1" class="ce0bg7b-n"/></linearGradient><linearGradient id="i7mB2nb" x1="13.261" x2="13.692" y1="25.667" y2="25.667" gradientUnits="userSpaceOnUse"><stop class="tgkl8ebfm"/><stop offset="1" class="wvqlanbxz"/></linearGradient><linearGradient id="iR15onA" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="iIEs1Hd" x1="18.825" x2="18.351" y1="24.378" y2="24.091" gradientUnits="userSpaceOnUse"><stop class="gqr8sybry"/><stop offset="1" class="lpb-gbbwk"/></linearGradient><linearGradient id="iFc3g8a" x1="15.749" x2="17.116" y1="25.981" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="i8i03nb" x1="16.03" x2="16.03" y1="10.724" y2="15.56" gradientUnits="userSpaceOnUse"><stop class="rlgwf126s"/><stop offset="1" class="l-4shobes"/></linearGradient><linearGradient id="ilgpd4F" x1="13.267" x2="15.457" y1="14.756" y2="14.756" gradientUnits="userSpaceOnUse"><stop offset=".01" class="jv6lqw6zm"/><stop offset="1" class="r3o1jnbex"/></linearGradient><linearGradient id="iRJZlyc" x1="18.593" x2="16.593" y1="15.245" y2="15.245" gradientUnits="userSpaceOnUse"><stop class="xxjj5obiq"/><stop offset="1" class="teavi7b3d"/></linearGradient><linearGradient id="iDDLGOd" x1="18.906" x2="18.453" y1="15.56" y2="15.56" gradientUnits="userSpaceOnUse"><stop class="ma_coc6av"/><stop offset="1" class="g9j7gtogb"/></linearGradient><linearGradient id="i9tL5Vd" x1="22.63" x2="20.036" y1="11.605" y2="13.448" gradientUnits="userSpaceOnUse"><stop offset=".453" class="yyuqaqb0l"/><stop offset="1" class="g_3g2umds"/></linearGradient><linearGradient id="in0SVNc" x1="22.059" x2="21.755" y1="8.558" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="a7sb80b8g"/><stop offset="1" class="f7acardkn"/></linearGradient><linearGradient id="iXQsZLe" x1="23.07" x2="22.804" y1="8.935" y2="9.896" gradientUnits="userSpaceOnUse"><stop class="a7sb80b8g"/><stop offset="1" class="f7acardkn"/></linearGradient><linearGradient id="ig9WlCc" x1="13.964" x2="13.685" y1="8.053" y2="8.053" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iXMCn2b" x1="18.574" x2="18.218" y1="7.458" y2="8.561" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="isgqYIc" x1="17.784" x2="14.463" y1="8.102" y2="8.597" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="i6GuzMe" x1="13.575" x2="15.036" y1="8.766" y2="8.815" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iekUSVc" x1="13.682" x2="14.501" y1="9.274" y2="9.245" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ivwITCu" x1="15.798" x2="19.34" y1="6.804" y2="5.535" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iSvpdbb" x1="15.653" x2="16.061" y1="8.388" y2="8.388" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iIC4mPL" x1="16.437" x2="15.991" y1="8.529" y2="8.522" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="i4GLinY" x1="16.113" x2="16.113" y1="8.851" y2="8.602" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="i6iWrbb" x1="17.315" x2="17.178" y1="7.659" y2="7.743" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irKophD" x1="15.402" x2="15.266" y1="7.659" y2="7.743" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibJWFGe" x1="17.322" x2="17.139" y1="6.728" y2="6.355" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iTWhwYc" x1="15.015" x2="14.497" y1="6.673" y2="6.456" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iZRjS7d" x1="14.001" x2="14.001" y1="5.797" y2="6.735" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-fairy-light" /></template>
<style>
.a2by3czaa {
  cx: 18.102px;
  cy: 7.932px;
  r: 0.433px;
}

.a48brs4te {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 1 1-.282-.312l4.235-3.836z");
}

.a7sb80b8g {
  stop-color: var(--svg-color--e5b5a5, #E5B5A5);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.aii5rr2eq {
  stop-color: var(--svg-color--eeb39e, #EEB39E);
}

.ajsjeuojy {
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.alg5_vbml {
  stop-color: var(--svg-color--e49d85, #E49D85);
  stop-opacity: 0;
}

.au9xqqdjp {
  d: path("M15.078 7.428a.388.388 0 0 0-.374.49h.75a.39.39 0 0 0-.376-.49");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b13j0jria {
  stop-color: var(--svg-color--f4baae, #F4BAAE);
}

.b68_6u4-q {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.029 9.294c-.22 0-.428-.052-.602-.143c-.06-.03-.124.037-.087.09c.146.221.4.368.689.368a.82.82 0 0 0 .688-.367c.038-.057-.026-.122-.086-.091a1.3 1.3 0 0 1-.602.143");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bs-ywhjno {
  stop-color: var(--svg-color--ffd1bd, #FFD1BD);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.c9v8_hpvm {
  stop-color: var(--svg-color--3f76a9, #3F76A9);
  stop-opacity: 0;
}

.ce0bg7b-n {
  stop-color: var(--svg-color--f5b7a1, #F5B7A1);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cw-i9xbem {
  stop-color: var(--svg-color--ba8d88, #BA8D88);
}

.d2gfipb4k {
  cx: 13.964px;
  cy: 7.932px;
  r: 0.726px;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d67-4i_lm {
  d: path("m18.125 5.115l.186.093a.855.855 0 0 1 .444.928l-.257 1.322c-.023.136-.113.228-.249.232h-.008s.024-.395.047-.627c.019-.188-.014-.245-.186-.417a.55.55 0 0 1-.164-.371v-.371a.25.25 0 0 0-.186-.232a7 7 0 0 0-1.703-.186c-.84 0-1.423.116-1.703.186a.226.226 0 0 0-.187.232v.37a.46.46 0 0 1-.163.372l-.07.07c-.094.07-.14.208-.14.324c.023.255.046.627.046.627l-.021-.001a.275.275 0 0 1-.259-.231l-.256-1.323a.89.89 0 0 1 .466-.904l.187-.093c.117-.07.233-.162.35-.255l.42-.44a.85.85 0 0 1 .956-.14c.234.07.49.07.723 0a1.05 1.05 0 0 1 1.027.232l.35.348c.093.116.21.185.35.255");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2kf81bwk {
  stop-color: var(--svg-color--4794c5, #4794C5);
  stop-opacity: 0;
}

.e593k4bfv {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.ek-1fff6o {
  d: path("M16.017 10.725c-.438.015-1.42.083-1.985.163c-.722.101-.765.71-.765.992v3.68h5.525v-3.68c0-.281-.043-.89-.764-.992a25 25 0 0 0-1.985-.163z");
}

.ep2-myb1w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.058 5.84v.39c-.004.065-.031.21-.113.27");
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.f7acardkn {
  stop-color: var(--svg-color--e5b5a5, #E5B5A5);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
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

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fwk98bb0c {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.439 7.053a.47.47 0 0 1-.215.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.g_3g2umds {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
  stop-opacity: 0;
}

.g9j7gtogb {
  stop-color: var(--svg-color--4db5ff, #4DB5FF);
  stop-opacity: 0;
}

.gdfj27b8p {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.134.147.326.443.456.87c.06.195.232.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.456-.87a.24.24 0 0 0 .066-.157v-.35z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gmn2w47zp {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
  stop-opacity: 0;
}

.gqr8sybry {
  stop-color: var(--svg-color--e9b9ad, #E9B9AD);
}

.greotackh {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.91 7.88l-.357.738c-.045.152.061.304.212.304h.32c.15 0 .257-.154.213-.304l-.217-.739c-.046-.164-.123-.164-.172 0");
}

.h0miccc8s {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M17.647 6.75v-.001h-.002l-.002-.002l-.005-.004l-.067-.047a1.23 1.23 0 0 0-.832-.16a.232.232 0 0 0 .072.458a.77.77 0 0 1 .513.095l.024.016l.004.003a.232.232 0 0 0 .295-.359");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hnwux9dcc {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.hxm_1sbuv {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .216-.373l.054-.894z");
}

.i7ccoc8qs {
  stop-color: var(--svg-color--3968ab, #3968AB);
}

.ikgiddbts {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.751 6.686c.187-.032.552-.023.804.173");
}

.ikgkim2qs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 8.558v.505a1 1 0 0 0 .433.824l.215.147");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.is_m6u3tw {
  stop-color: var(--svg-color--c36f72, #C36F72);
  stop-opacity: 0;
}

.itfpqxb5a {
  d: path("M17.323 7.765a.37.37 0 0 0-.1-.201l-.113.124l.05.1z");
}

.iwsb7zzqk {
  stop-color: var(--svg-color--f5b7a1, #F5B7A1);
}

.j4lcbbc1h {
  cx: 18.102px;
  cy: 7.932px;
  r: 0.433px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.jv6lqw6zm {
  stop-color: var(--svg-color--4f6fa1, #4F6FA1);
}

.k_-pp4tvx {
  d: path("m17.753 5.486l-1.339.446a.455.455 0 0 0 .205.884l1.33-.178z");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.kcor2lvvo {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
}

.kgna9sqpj {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
  stop-opacity: 0;
}

.l-4shobes {
  stop-color: var(--svg-color--358dea, #358DEA);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lpb-gbbwk {
  stop-color: var(--svg-color--e9b9ad, #E9B9AD);
  stop-opacity: 0;
}

.ls3dj269w {
  fill: var(--svg-color--3c8aea, #3C8AEA);
  d: path("M13.264 21.733V16.26l5.528.056c0 .348.063.666.09.765l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.ma_coc6av {
  stop-color: var(--svg-color--51a3e8, #51A3E8);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.muudq6bym {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.067 7.31a.61.61 0 0 1 .59.46a.12.12 0 0 1-.117.149h-.97a.1.1 0 0 1-.099-.119c.055-.278.3-.49.596-.49");
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nb-v65buu {
  fill: var(--svg-color--f2b7a1, #F2B7A1);
  d: path("m21.499 12.27l-3.145-1.206l-.136 2.175l3.578 1.368c.185.083.651.2 1.039 0s.515-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0V8.51a.404.404 0 0 0-.805-.035c-.013.162-.03.366-.047.6c-.038.494.276.836.437.961z");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.njax42eii {
  stop-color: var(--svg-color--f1bdad, #F1BDAD);
}

.nkm4r8_8f {
  stop-color: var(--svg-color--4780ac, #4780AC);
}

.nl4f7twra {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  rx: 0.352px;
}

.no129_bju {
  fill: var(--svg-color--fbc5b5, #FBC5B5);
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.nov_osbjm {
  stop-color: var(--svg-color--e19d8a, #E19D8A);
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p3xpydy4e {
  fill: var(--svg-color--eab8a0, #EAB8A0);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.128c.1.102.144.418-.094.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.p8zhg8wps {
  stop-color: var(--svg-color--c36f72, #C36F72);
}

.pb1pwib-r {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .005-4.88a3.454 3.454 0 0 1 4.881-.006l1.19 1.19c.337.337.601.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl0mjl3nz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.481 6.912c.142-.126.453-.258.838-.197");
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.ptfvfcbrt {
  stop-color: var(--svg-color--435e8c, #435E8C);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.q9tdvibpa {
  d: path("M13.786 7.04c0-.116.046-.255.14-.324l.07-.07a.46.46 0 0 0 .163-.371v-.371c0-.116.07-.21.187-.232c.28-.07.863-.186 1.703-.186s1.423.116 1.703.186a.25.25 0 0 1 .186.232v.37c0 .14.07.28.164.372c.218.153.204.237.186.417a22 22 0 0 0-.047.627h.008l-.115 1.721c-.07.77-.675 1.306-1.396 1.306H15.34c-.744 0-1.326-.536-1.396-1.306c-.06-.79-.087-1.582-.16-2.37");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qqdmv7_7m {
  fill: var(--svg-color--000, #000);
  d: path("M16.755 7.816c0-.123.099-.222.223-.222a.22.22 0 0 1 .197.325h-.393a.2.2 0 0 1-.027-.103");
}

.quxai4aum {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3o1jnbex {
  stop-color: var(--svg-color--3391ee, #3391EE);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r9m8_svvg {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.re9d71n0d {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.128c.1.102.144.418-.094.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rlgwf126s {
  stop-color: var(--svg-color--43abff, #43ABFF);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_f01nb2h {
  stop-color: var(--svg-color--4b3866, #4B3866);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s3qcrxbjw {
  stop-color: var(--svg-color--d3947d, #D3947D);
}

.s8ovo2bbk {
  fill: var(--svg-color--242324, #242324);
  d: path("m18.125 5.115l.186.093a.855.855 0 0 1 .444.928l-.257 1.322c-.023.136-.113.228-.249.232h-.008s.024-.395.047-.627c.019-.188-.014-.245-.186-.417a.55.55 0 0 1-.164-.371v-.371a.25.25 0 0 0-.186-.232a7 7 0 0 0-1.703-.186c-.84 0-1.423.116-1.703.186a.226.226 0 0 0-.187.232v.37a.46.46 0 0 1-.163.372l-.07.07c-.094.07-.14.208-.14.324c.023.255.046.627.046.627l-.021-.001a.275.275 0 0 1-.259-.231l-.256-1.323a.89.89 0 0 1 .466-.904l.187-.093c.117-.07.233-.162.35-.255l.42-.44a.85.85 0 0 1 .956-.14c.234.07.49.07.723 0a1.05 1.05 0 0 1 1.027.232l.35.348c.093.116.21.185.35.255");
}

.saunobcmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 12.667l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.sb1zj3bbu {
  stop-color: var(--svg-color--fccbb7, #FCCBB7);
  stop-opacity: 0;
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.t0dfidbsh {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
  stop-opacity: 0;
}

.t142bdb_h {
  cx: 18.101px;
  cy: 7.932px;
  r: 0.726px;
}

.t16p7zajb {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.863-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.t2qxtb2ul {
  stop-color: var(--svg-color--e5af9f, #E5AF9F);
  stop-opacity: 0;
}

.t6m6gnbiw {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 0 0-.284.31l1.82 1.668l-.84.085a.21.21 0 0 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.tdjl0hblu {
  stop-color: var(--svg-color--fccbb7, #FCCBB7);
}

.teavi7b3d {
  stop-color: var(--svg-color--3b9bf4, #3B9BF4);
  stop-opacity: 0;
}

.tgkl8ebfm {
  stop-color: var(--svg-color--f1b69f, #F1B69F);
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tv4w4-j7e {
  d: path("M15.433 7.77c0-.125-.102-.208-.13-.234l-.125.122l.077.157z");
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.tzpzpobmp {
  fill: var(--svg-color--000, #000);
  d: path("M15.3 7.816a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.325h.393a.2.2 0 0 0 .026-.103");
}

.u2p7zvbzn {
  stop-color: var(--svg-color--2851b6, #2851B6);
  stop-opacity: 0;
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.urtx-5blf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.949 7.51c.028.037-.03.082-.096.132c-.066.049-.114.083-.142.046s.003-.107.069-.156s.141-.059.169-.022");
}

.usyhe_b6f {
  d: path("M13.264 21.733V16.26l5.528.056c0 .348.063.666.09.765l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uu9c01xwt {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.uvyxh01-z {
  stop-color: var(--svg-color--2851b6, #2851B6);
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v1jna4b3w {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.988 7.31a.61.61 0 0 0-.589.46a.12.12 0 0 0 .117.149h.97a.1.1 0 0 0 .098-.119a.61.61 0 0 0-.596-.49");
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
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

.w-1p8nn-n {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.863 7.808l-.231.74a.234.234 0 0 0 .226.303h.342c.16 0 .273-.154.226-.304l-.23-.739c-.05-.164-.282-.164-.333 0");
}

.waah2bcle {
  stop-color: var(--svg-color--3968ab, #3968AB);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wh5hl9ggo {
  d: path("m15.863 7.808l-.231.74a.234.234 0 0 0 .226.303h.342c.16 0 .273-.154.226-.304l-.23-.739c-.05-.164-.282-.164-.333 0");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wibfg_jba {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
}

.wvqlanbxz {
  stop-color: var(--svg-color--f1b69f, #F1B69F);
  stop-opacity: 0;
}

.wwuyjbert {
  cx: 14.961px;
  cy: 7.594px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x3rydqk_a {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M14.388 6.75v-.001h.001l.002-.002l.005-.004l.068-.047a1.23 1.23 0 0 1 .832-.16a.232.232 0 0 1-.073.458a.77.77 0 0 0-.513.095l-.027.019a.232.232 0 0 1-.295-.358");
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xsno6rw2t {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
  stop-opacity: 0;
}

.xxjj5obiq {
  stop-color: var(--svg-color--4db6ff, #4DB6FF);
}

.y-5m-ibgn {
  cx: 14.961px;
  cy: 7.594px;
  rx: 0.169px;
  ry: 0.086px;
}

.y0ghjsngh {
  d: path("M16.977 7.428a.388.388 0 0 1 .374.49h-.75a.39.39 0 0 1 .376-.49");
}

.y39x50mqx {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
}

.y3su9tbbh {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .284.31l-1.82 1.668l.84.085a.21.21 0 0 1-.043.418l-1.21-.124l-.955.875a.21.21 0 1 1-.284-.31z");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ykkax8bmp {
  stop-color: var(--svg-color--d3a086, #D3A086);
}

.yn_cprukr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.025-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .283-.312l-4.235-3.836z");
}

.yv8187b0r {
  stop-color: var(--svg-color--c38488, #C38488);
}

.yvzenumps {
  d: path("M16.949 7.51c.028.037-.03.082-.096.132c-.066.049-.114.083-.142.046s.003-.107.069-.156s.141-.059.169-.022");
}

.ywk-_ln5y {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
}

.ywqn4-bmn {
  stop-color: var(--svg-color--f1bdad, #F1BDAD);
  stop-opacity: 0;
}

.yyuqaqb0l {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
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

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z75qbob3v {
  cx: 13.964px;
  cy: 7.932px;
  r: 0.433px;
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zh46g387g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 8.935v.258a.9.9 0 0 1-.25.617v0");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zss1t2k2l {
  stop-color: var(--svg-color--ebb3a3, #EBB3A3);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
