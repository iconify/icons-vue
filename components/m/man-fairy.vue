<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDExWld)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#imYmvCd)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iecL5Pb)"><path fill="url(#i5I72Pc)" class="pb1pwib-r"/><path fill="url(#iX1BTZW)" class="pb1pwib-r"/></g><g filter="url(#i360hQd)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#if9LwTb)"><path class="g11vnob-s"/></g><g filter="url(#irgtWKc)"><path class="yn_cprukr"/></g><g filter="url(#ivovSHc)"><path class="w2mg53b0k"/></g><g filter="url(#iEBpd0c)"><path class="tn00ksbky"/></g><g filter="url(#iYCRBpx)"><rect class="dx3gqo8_o"/><rect fill="url(#i8a16yi)" class="egop4ni4l"/></g><g filter="url(#ifiE1bb)"><path fill="url(#ioitlCc)" class="t16p7zajb"/></g><path fill="url(#i5Ao9Gd)" class="t16p7zajb"/><path fill="url(#i8KfH3d)" class="t16p7zajb"/><path fill="url(#iEdEbnd)" class="t16p7zajb"/><path class="n-gofxbqk"/><path fill="url(#iGgZmQl)" class="qqobt5tvr"/><path fill="url(#iVakvLc)" class="qqobt5tvr"/><path fill="url(#i3gy0Bb)" class="qqobt5tvr"/><path fill="url(#iuPT4Kc)" class="qqobt5tvr"/><path fill="url(#iHyYx2b)" class="qqobt5tvr"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><g filter="url(#iMCluJe)"><path fill="url(#iVQsxVd)" class="fwk98bb0c"/><path fill="url(#i1oqYKe)" class="fwk98bb0c"/><path fill="url(#i47ILGc)" class="fwk98bb0c"/></g><path fill="url(#iuP6NMd)" class="wke8dtqov"/><path fill="url(#iDv7Hjb)" class="wke8dtqov"/><g filter="url(#ii04RWQ)"><path class="bkb3ezqdl"/><path fill="url(#i40CHhd)" class="ajsjeuojy"/><path fill="url(#iOc4Lne)" class="ajsjeuojy"/></g><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#itC8Jgb)" class="z30kudb-o"/><g filter="url(#ifrzK6c)"><path class="nkr0e_-9b"/><path fill="url(#ilCAz0c)" class="k-27-x9ja"/><path fill="url(#iwzkgkd)" class="k-27-x9ja"/></g><g filter="url(#iNeZ7Zd)"><path class="v7sz3oo0t"/></g><path fill="url(#iDR5xSb)" class="dixb6cljt"/><g filter="url(#iS53otb)"><path class="r_t84mbpt"/><path fill="url(#iSGVMGe)" class="pvigboqtr"/></g><path fill="url(#inrcRqb)" class="pvigboqtr"/><path fill="url(#iEr62fd)" class="pvigboqtr"/><path fill="url(#iFc0eqy)" class="u5zvm6bcl"/><path fill="url(#iZeEFzX)" class="u5zvm6bcl"/><path fill="url(#i7zEfhH)" class="u5zvm6bcl"/><path fill="url(#iVRHTBe)" class="u5zvm6bcl"/><path fill="url(#iK804bd)" class="u5zvm6bcl"/><path fill="url(#iaW1cmd)" class="u5zvm6bcl"/><path fill="url(#iqcIBfc)" class="u5zvm6bcl"/><path fill="url(#i4ii3Od)" class="gdfj27b8p"/><circle fill="url(#iIzeW6c)" class="cb05b8bzs"/><g filter="url(#i4b9U4b)"><circle fill="url(#imsOK0b)" class="q3uwrubmd"/></g><g filter="url(#ixaHbMv)"><circle fill="url(#ipGbOCe)" class="pa1p9k54q"/><circle fill="url(#iAcUbKc)" class="pa1p9k54q"/></g><g filter="url(#if5mQue)"><circle class="iy1wgjb0b"/><circle fill="url(#iESmT0d)" class="ir49hyb2a"/><circle fill="url(#iOZtX4c)" class="ir49hyb2a"/></g><path fill="url(#i50m6jb)" class="n_fokp-oy"/><path fill="url(#iEMoFMd)" class="n_fokp-oy"/><path fill="url(#iqFNkiP)" class="n_fokp-oy"/><path fill="url(#iG46pjd)" class="n_fokp-oy"/><path fill="url(#i0tES8c)" class="n_fokp-oy"/><g filter="url(#iUimZWb)"><path class="izxoe265w"/><path fill="url(#ihrvXPd)" class="ppjzfv2uj"/><path fill="url(#iRLZ1hj)" class="ppjzfv2uj"/><path fill="url(#irU1Xdd)" class="ppjzfv2uj"/><path fill="url(#i0oVOBq)" class="ppjzfv2uj"/><path fill="url(#iLllY9d)" class="ppjzfv2uj"/><path fill="url(#ilB7MWd)" class="ppjzfv2uj"/></g><path fill="url(#iAN36Dc)" class="ppjzfv2uj"/><path fill="url(#ibQIWWc)" class="ppjzfv2uj"/><path fill="url(#iEvWI4c)" class="ppjzfv2uj"/><g filter="url(#ixNLy4L)"><path class="uad7v8byj"/></g><g filter="url(#ioOCDVz)"><path class="irh2bxm9m"/><path fill="url(#iC83VGb)" class="he7nglb0t"/><path fill="url(#iuJMyBe)" class="he7nglb0t"/><path fill="url(#iJQW9id)" class="he7nglb0t"/></g><g filter="url(#iyBBbpc)"><path stroke="url(#i6NpZNb)" class="mh-zgv20h"/></g><path class="hmkofncca"/><path class="pk_-ivm9h"/><path fill="url(#iJsAafd)" class="ocwsjsbax"/><path class="z71en7xch"/><g filter="url(#iPX33Wc)"><path class="adkn4tb0a"/><path fill="url(#iF6OfPb)" class="n95udob9s"/></g><g filter="url(#iXU8d8b)"><path fill="url(#i9yHn2c)" class="dajq0xbdk"/></g><path class="bu_3yebqq"/><path fill="url(#irZp3Gd)" class="yx_6dvgle"/><path class="utbg4t6zg"/><g filter="url(#iILrCbe)"><path fill="url(#ixZcwDv)" class="jgzd_hblw"/></g><g filter="url(#iZfxr6b)"><ellipse transform="rotate(-27.914 14.944 7.55)" class="wte04qb6c"/><ellipse fill="url(#imwWDzb)" transform="rotate(-27.914 14.944 7.55)" class="dlg3h11nd"/></g><g filter="url(#izMenfb)"><path fill="url(#iExlOJA)" clip-rule="evenodd" class="na4val4_a"/></g><g filter="url(#iIMvAlc)"><path class="qn_a-dbej"/></g><g filter="url(#iNufOhb)"><path fill="url(#ii4mxbb)" clip-rule="evenodd" class="kkalbobgn"/></g><g filter="url(#igTYbPj)"><path class="ddh5kcbbf"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iVakvLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68754 -5.0625 2.53124 -.34377 16.78 21.98)" gradientUnits="userSpaceOnUse"><stop class="uvyxh01-z"/><stop offset="1" class="u2p7zvbzn"/></radialGradient><radialGradient id="i3gy0Bb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.125 15.9 2.484)scale(.88884 .66004)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="kcor2lvvo"/><stop offset="1" class="t0dfidbsh"/></radialGradient><radialGradient id="iHyYx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 -4.56052 .72812 .03493 14.75 21.79)" gradientUnits="userSpaceOnUse"><stop class="ywk-_ln5y"/><stop offset="1" class="quxai4aum"/></radialGradient><radialGradient id="i47ILGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17187 2.9198 -.50904 -.02996 15.382 25.78)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="qw90o_byh"/><stop offset="1" class="ampfxn_6u"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iOc4Lne" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="lhl06-bha"/><stop offset="1" class="l473kpbea"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="itC8Jgb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.564 3.998 7.72)scale(.69215 .70844)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="qtbbj-y7w"/><stop offset="1" class="ocvnedcjc"/></radialGradient><radialGradient id="ilCAz0c" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.302)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="y9drs-b-r"/><stop offset=".995" class="o-5xddb6x"/></radialGradient><radialGradient id="iwzkgkd" cx="0" cy="0" r="1" gradientTransform="rotate(119.914 -.645 10.001)scale(.98695 .40009)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="s2zpt4bdz"/><stop offset="1" class="iwjfcrbly"/></radialGradient><radialGradient id="iSGVMGe" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.875 -2.0833 .9722 21.944 8.247)" gradientUnits="userSpaceOnUse"><stop class="em3moybkz"/><stop offset="1" class="mtf4q5bqt"/></radialGradient><radialGradient id="inrcRqb" cx="0" cy="0" r="1" gradientTransform="matrix(.26644 -4.07813 1.3228 .08642 23.615 13.013)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="er1wy7bvb"/><stop offset="1" class="yv86un7fh"/></radialGradient><radialGradient id="iEr62fd" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 6.033 12.706)scale(.35113 2.04974)" gradientUnits="userSpaceOnUse"><stop class="km2h82bty"/><stop offset="1" class="en0ycmbdo"/></radialGradient><radialGradient id="i7zEfhH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.194 10.709)" gradientUnits="userSpaceOnUse"><stop class="ptfvfcbrt"/><stop offset="1" class="c9v8_hpvm"/></radialGradient><radialGradient id="iVRHTBe" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.147 8.847)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="y39x50mqx"/><stop offset="1" class="gmn2w47zp"/></radialGradient><radialGradient id="iK804bd" cx="0" cy="0" r="1" gradientTransform="matrix(1.67188 0 0 .4274 16.843 10.709)" gradientUnits="userSpaceOnUse"><stop class="nkm4r8_8f"/><stop offset="1" class="e2kf81bwk"/></radialGradient><radialGradient id="i4ii3Od" cx="0" cy="0" r="1" gradientTransform="matrix(.69599 1.27545 -2.68865 1.46713 15.147 10.486)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="muaav7b6p"/><stop offset="1" class="mudxz8mau"/></radialGradient><radialGradient id="iIzeW6c" cx="0" cy="0" r="1" gradientTransform="matrix(.77184 0 0 1.35073 13.202 7.892)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iAcUbKc" cx="0" cy="0" r="1" gradientTransform="matrix(.36361 -.26476 .3022 .41501 18.284 7.776)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iESmT0d" cx="0" cy="0" r="1" gradientTransform="matrix(.36122 -.66438 .38886 .21142 18.102 8.253)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iOZtX4c" cx="0" cy="0" r="1" gradientTransform="rotate(44.71 -.535 25.979)scale(.16047 .20686)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iqFNkiP" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.77623 -4.31177 0 16.24 7.192)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="iG46pjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5749 .70756 0 17.056 7.333)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i0tES8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.61175 .76076 0 15.052 7.318)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ihrvXPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51153 1.94816 -3.31302 -2.57049 17.648 4.5)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="irU1Xdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.08114 -.87637 .4304 -.03985 14.205 6.29)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="i0oVOBq" cx="0" cy="0" r="1" gradientTransform="matrix(.37788 -.86492 .7054 .30819 17.883 7.128)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iLllY9d" cx="0" cy="0" r="1" gradientTransform="rotate(51.134 3.547 18.445)scale(.69587 .6144)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="ilB7MWd" cx="0" cy="0" r="1" gradientTransform="matrix(.6382 -1.33517 .46132 .2205 17.866 6.036)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iAN36Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.11487 .44639 -.73388 .18885 16.33 4.108)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="ibQIWWc" cx="0" cy="0" r="1" gradientTransform="matrix(.48687 .70326 -1.46347 1.01317 14.097 4.664)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iEvWI4c" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 7.624 4.762)scale(3.47692 4.35062)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="i6NpZNb" cx="0" cy="0" r="1" gradientTransform="matrix(.01082 -.2759 .82768 .03246 15.987 9.657)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iJsAafd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39724 -.47003 0 16.983 7.739)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iF6OfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10174 -.1311 .1805 -.14007 16.884 7.629)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irZp3Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39726 -.47006 0 15.064 7.739)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imwWDzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0034 -.21675 .26054 -.00408 14.938 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iExlOJA" cx="0" cy="0" r="1" gradientTransform="matrix(.08655 -.35704 .78329 .18989 17.102 6.925)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="ii4mxbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.08655 -.35704 .78329 -.18989 14.946 6.925)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="iDExWld" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1143" result="effect2_innerShadow_4002_1143"/></filter><filter id="imYmvCd" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1143" result="effect2_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1143" result="effect3_innerShadow_4002_1143"/></filter><filter id="iecL5Pb" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1143" result="effect2_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1143" result="effect3_innerShadow_4002_1143"/></filter><filter id="i360hQd" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="if9LwTb" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1143" result="effect2_dropShadow_4002_1143"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1143" result="shape"/></filter><filter id="irgtWKc" width="6.45" height="6.548" x="9.619" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1143" result="effect2_dropShadow_4002_1143"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1143" result="shape"/></filter><filter id="ivovSHc" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1143" result="effect2_dropShadow_4002_1143"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1143" result="shape"/></filter><filter id="iEBpd0c" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1143" result="effect2_dropShadow_4002_1143"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1143" result="shape"/></filter><filter id="iYCRBpx" width=".989" height="4.833" x="22.354" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="ifiE1bb" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="iMCluJe" width="2.97" height="8.306" x="13.261" y="21.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.658824 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="ii04RWQ" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.576471 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="ifrzK6c" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.564706 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.423529 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1143" result="effect2_innerShadow_4002_1143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.619608 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1143" result="effect3_innerShadow_4002_1143"/></filter><filter id="iNeZ7Zd" width="1.692" height="1.561" x="6.723" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="iS53otb" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.556863 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="i4b9U4b" width="1.875" height="1.875" x="12.998" y="6.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".25"/></filter><filter id="ixaHbMv" width="1.719" height="1.719" x="17.386" y="6.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="if5mQue" width="1.875" height="1.875" x="17.183" y="6.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".25"/></filter><filter id="iUimZWb" width="5.543" height="3.638" x="13.253" y="4.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="ixNLy4L" width="2.274" height="2.679" x="14.782" y="6.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".375"/></filter><filter id="ioOCDVz" width="1.025" height="1.379" x="15.512" y="7.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".05"/></filter><filter id="iyBBbpc" width="1.615" height=".672" x="15.217" y="9.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".025"/></filter><filter id="iPX33Wc" width=".457" height=".418" x="16.604" y="7.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".05"/></filter><filter id="iXU8d8b" width=".615" height=".625" x="16.917" y="7.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".1"/></filter><filter id="iILrCbe" width=".657" height=".681" x="14.963" y="7.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".1"/></filter><filter id="iZfxr6b" width=".513" height=".421" x="14.688" y="7.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".05"/></filter><filter id="izMenfb" width="1.144" height=".864" x="16.58" y="6.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="iIMvAlc" width="1.229" height=".699" x="16.538" y="6.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".1"/></filter><filter id="iNufOhb" width="1.144" height=".864" x="14.324" y="6.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1143"/></filter><filter id="igTYbPj" width="1.229" height=".699" x="14.282" y="6.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1143" stdDeviation=".1"/></filter><linearGradient id="i5I72Pc" x1="8.528" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="iGgZmQl" x1="13.264" x2="15.031" y1="19.026" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="i7ccoc8qs"/><stop offset="1" class="waah2bcle"/></linearGradient><linearGradient id="iuPT4Kc" x1="19.343" x2="17.937" y1="18.573" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="hnwux9dcc"/><stop offset="1" class="xsno6rw2t"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iVQsxVd" x1="15.288" x2="12.882" y1="25.263" y2="25.294" gradientUnits="userSpaceOnUse"><stop offset=".113" class="dwuisxbps"/><stop offset="1" class="jot7ajumx"/></linearGradient><linearGradient id="i1oqYKe" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="xnu-7l9ks"/><stop offset="1" class="a4yl9qxqh"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="i40CHhd" x1="18.757" x2="18.351" y1="24.364" y2="24.091" gradientUnits="userSpaceOnUse"><stop offset=".202" class="o74y7ni4m"/><stop offset="1" class="c_2-erh-s"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="iDR5xSb" x1="8.209" x2="7.426" y1="14.716" y2="15.269" gradientUnits="userSpaceOnUse"><stop offset=".337" class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><linearGradient id="iFc0eqy" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="rlgwf126s"/><stop offset="1" class="l-4shobes"/></linearGradient><linearGradient id="iZeEFzX" x1="13.267" x2="15.457" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop offset=".01" class="jv6lqw6zm"/><stop offset="1" class="r3o1jnbex"/></linearGradient><linearGradient id="iaW1cmd" x1="18.593" x2="16.593" y1="15.23" y2="15.23" gradientUnits="userSpaceOnUse"><stop class="xxjj5obiq"/><stop offset="1" class="teavi7b3d"/></linearGradient><linearGradient id="iqcIBfc" x1="18.906" x2="18.453" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="ma_coc6av"/><stop offset="1" class="g9j7gtogb"/></linearGradient><linearGradient id="imsOK0b" x1="13.936" x2="13.654" y1="8.015" y2="8.015" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="ipGbOCe" x1="18.598" x2="18.238" y1="7.412" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i50m6jb" x1="17.799" x2="14.441" y1="8.063" y2="8.564" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iEMoFMd" x1="13.651" x2="14.668" y1="9.249" y2="9.117" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iRLZ1hj" x1="13.886" x2="15.162" y1="7.775" y2="5.507" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iC83VGb" x1="15.644" x2="16.057" y1="8.353" y2="8.353" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iuJMyBe" x1="16.437" x2="15.986" y1="8.495" y2="8.489" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iJQW9id" x1="16.11" x2="16.11" y1="8.822" y2="8.57" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i9yHn2c" x1="17.324" x2="17.187" y1="7.616" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixZcwDv" x1="15.39" x2="15.252" y1="7.615" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-fairy" /></template>
<style>
.a4yl9qxqh {
  stop-color: var(--svg-color--fcb63b, #FCB63B);
  stop-opacity: 0;
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.adkn4tb0a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.954 7.466c.028.037-.03.082-.097.132c-.066.05-.115.084-.143.047s.003-.108.07-.157c.066-.05.142-.06.17-.022");
}

.ajsjeuojy {
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.ampfxn_6u {
  stop-color: var(--svg-color--e9af19, #E9AF19);
  stop-opacity: 0;
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bkb3ezqdl {
  fill: var(--svg-color--ffc93e, #FFC93E);
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.bu_3yebqq {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.972 7.263a.614.614 0 0 0-.596.466a.12.12 0 0 0 .118.15h.98a.1.1 0 0 0 .1-.12a.616.616 0 0 0-.602-.496");
}

.c_2-erh-s {
  stop-color: var(--svg-color--ffc93f, #FFC93F);
  stop-opacity: 0;
}

.c9v8_hpvm {
  stop-color: var(--svg-color--3f76a9, #3F76A9);
  stop-opacity: 0;
}

.cb05b8bzs {
  cx: 13.936px;
  cy: 7.892px;
  r: 0.734px;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dajq0xbdk {
  d: path("M17.333 7.723a.37.37 0 0 0-.102-.203l-.114.125l.052.1z");
}

.ddh5kcbbf {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.532 6.86c.092-.085.353-.229.73-.193");
}

.dixb6cljt {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.129c.1.103.144.418-.094.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.dlg3h11nd {
  cx: 14.944px;
  cy: 7.55px;
  rx: 0.171px;
  ry: 0.087px;
}

.dwuisxbps {
  stop-color: var(--svg-color--ffd240, #FFD240);
}

.dx3gqo8_o {
  width: 0.689px;
  height: 4.633px;
  x: 22.354px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
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

.egop4ni4l {
  width: 0.689px;
  height: 4.633px;
  x: 22.354px;
  y: 4.997px;
  rx: 0.345px;
}

.em3moybkz {
  stop-color: var(--svg-color--f2b336, #F2B336);
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.en0ycmbdo {
  stop-color: var(--svg-color--f2b133, #F2B133);
  stop-opacity: 0;
}

.er1wy7bvb {
  stop-color: var(--svg-color--ffdb3e, #FFDB3E);
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.ft5dv1b6b {
  fill: none;
}

.fwk98bb0c {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.439 7.053a.47.47 0 0 1-.215.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g9j7gtogb {
  stop-color: var(--svg-color--4db5ff, #4DB5FF);
  stop-opacity: 0;
}

.gdfj27b8p {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.134.147.326.443.456.87c.06.195.232.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.456-.87a.24.24 0 0 0 .066-.157v-.35z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gmn2w47zp {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.he7nglb0t {
  d: path("m15.856 7.767l-.233.747a.237.237 0 0 0 .229.308h.345a.238.238 0 0 0 .23-.308l-.234-.747c-.05-.166-.284-.166-.337 0");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hmkofncca {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.024 9.269a1.3 1.3 0 0 1-.609-.145c-.06-.03-.125.038-.087.092a.83.83 0 0 0 .696.372a.83.83 0 0 0 .697-.372c.038-.057-.027-.122-.087-.092a1.3 1.3 0 0 1-.61.145");
}

.hnwux9dcc {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i7ccoc8qs {
  stop-color: var(--svg-color--3968ab, #3968AB);
}

.ir49hyb2a {
  cx: 18.12px;
  cy: 7.892px;
  r: 0.438px;
}

.irh2bxm9m {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.856 7.767l-.233.747a.237.237 0 0 0 .229.308h.345a.238.238 0 0 0 .23-.308l-.234-.747c-.05-.166-.284-.166-.337 0");
}

.iwjfcrbly {
  stop-color: var(--svg-color--d08154, #D08154);
  stop-opacity: 0;
}

.iy1wgjb0b {
  cx: 18.12px;
  cy: 7.892px;
  r: 0.438px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.izxoe265w {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m18.143 5.043l.19.094c.33.164.518.54.447.938l-.26 1.337c-.022.138-.114.231-.25.235c.015-.222.03-.58.035-.636c.02-.19-.01-.246-.185-.42a.55.55 0 0 1-.165-.375V5.84a.25.25 0 0 0-.19-.235a7.2 7.2 0 0 0-1.721-.188c-.85 0-1.44.118-1.723.188a.23.23 0 0 0-.188.235v.375c0 .14-.047.281-.165.375l-.071.07c-.095.071-.142.218-.142.335c.006.069.015.463.026.627a.28.28 0 0 1-.262-.234l-.26-1.337a.9.9 0 0 1 .473-.915c.446-.196.608-.492.967-.798a.86.86 0 0 1 .967-.14c.236.07.496.07.732 0a1.06 1.06 0 0 1 1.038.234l.354.352a1 1 0 0 0 .353.258");
}

.jgzd_hblw {
  d: path("M15.42 7.728c0-.126-.102-.21-.13-.236l-.126.122l.077.158z");
}

.jot7ajumx {
  stop-color: var(--svg-color--f6ae2e, #F6AE2E);
}

.jv6lqw6zm {
  stop-color: var(--svg-color--4f6fa1, #4F6FA1);
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kcor2lvvo {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
}

.kkalbobgn {
  fill-rule: evenodd;
  d: path("M15.242 6.922c-.317-.03-.52.094-.57.14a.208.208 0 1 1-.28-.306c.134-.124.453-.288.888-.248a.208.208 0 0 1-.038.414");
}

.km2h82bty {
  stop-color: var(--svg-color--f2b133, #F2B133);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l-4shobes {
  stop-color: var(--svg-color--358dea, #358DEA);
}

.l473kpbea {
  stop-color: var(--svg-color--ffe447, #FFE447);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhl06-bha {
  stop-color: var(--svg-color--ffe447, #FFE447);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.ma_coc6av {
  stop-color: var(--svg-color--51a3e8, #51A3E8);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mh-zgv20h {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.024 9.269a1.3 1.3 0 0 1-.609-.145c-.06-.03-.125.038-.087.092a.83.83 0 0 0 .696.372a.83.83 0 0 0 .697-.372c.038-.057-.027-.122-.087-.092a1.3 1.3 0 0 1-.61.145Z");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mtf4q5bqt {
  stop-color: var(--svg-color--f2b336, #F2B336);
  stop-opacity: 0;
}

.muaav7b6p {
  stop-color: var(--svg-color--f79d25, #F79D25);
}

.mudxz8mau {
  stop-color: var(--svg-color--ffbe35, #FFBE35);
}

.n_fokp-oy {
  d: path("M13.781 7.623a13 13 0 0 1-.025-.633c0-.117.047-.258.141-.328l.071-.07a.47.47 0 0 0 .165-.376V5.84c0-.118.071-.212.189-.235c.283-.07.873-.188 1.722-.188c.85 0 1.44.118 1.722.188a.25.25 0 0 1 .19.235v.375c0 .14.07.281.164.375c.221.155.207.24.19.422c-.007.057-.024.526-.04.634l-.117 1.74c-.07.78-.683 1.322-1.412 1.322h-1.412c-.753 0-1.342-.543-1.412-1.321z");
}

.n-gofxbqk {
  fill: var(--svg-color--3c8aea, #3C8AEA);
  d: path("M13.264 21.733V16.26l5.528.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n95udob9s {
  d: path("M16.954 7.466c.028.037-.03.082-.097.132c-.066.05-.115.084-.143.047s.003-.108.07-.157c.066-.05.142-.06.17-.022");
}

.na4val4_a {
  fill-rule: evenodd;
  d: path("M16.807 6.922c.317-.03.52.094.569.14a.208.208 0 1 0 .281-.306c-.134-.124-.453-.288-.889-.248a.208.208 0 1 0 .04.414");
}

.nkm4r8_8f {
  stop-color: var(--svg-color--4780ac, #4780AC);
}

.nkr0e_-9b {
  fill: var(--svg-color--ffc337, #FFC337);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o74y7ni4m {
  stop-color: var(--svg-color--f4c04c, #F4C04C);
}

.ocvnedcjc {
  stop-color: var(--svg-color--d59d43, #D59D43);
}

.ocwsjsbax {
  d: path("M16.984 7.382a.392.392 0 0 1 .378.496h-.758a.394.394 0 0 1 .38-.496");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pa1p9k54q {
  cx: 18.12px;
  cy: 7.892px;
  r: 0.734px;
}

.pb1pwib-r {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .005-4.88a3.454 3.454 0 0 1 4.881-.006l1.19 1.19c.337.337.601.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pk_-ivm9h {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.075 7.263c.287 0 .53.198.596.466a.12.12 0 0 1-.118.15h-.981a.1.1 0 0 1-.1-.12a.615.615 0 0 1 .603-.496");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppjzfv2uj {
  d: path("m18.143 5.043l.19.094c.33.164.518.54.447.938l-.26 1.337c-.022.138-.114.231-.25.235c.015-.222.03-.58.035-.636c.02-.19-.01-.246-.185-.42a.55.55 0 0 1-.165-.375V5.84a.25.25 0 0 0-.19-.235a7.2 7.2 0 0 0-1.721-.188c-.85 0-1.44.118-1.723.188a.23.23 0 0 0-.188.235v.375c0 .14-.047.281-.165.375l-.071.07c-.095.071-.142.218-.142.335c.006.069.015.463.026.627a.28.28 0 0 1-.262-.234l-.26-1.337a.9.9 0 0 1 .473-.915c.446-.196.608-.492.967-.798a.86.86 0 0 1 .967-.14c.236.07.496.07.732 0a1.06 1.06 0 0 1 1.038.234l.354.352a1 1 0 0 0 .353.258");
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.ptfvfcbrt {
  stop-color: var(--svg-color--435e8c, #435E8C);
}

.pvigboqtr {
  d: path("m21.499 12.27l-3.145-1.206l-.136 2.175l3.578 1.368c.185.083.651.2 1.039 0s.515-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.038.494.276.836.437.961z");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q3uwrubmd {
  cx: 13.936px;
  cy: 7.892px;
  r: 0.438px;
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qn_a-dbej {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.517 6.86c-.092-.085-.353-.229-.73-.193");
}

.qqobt5tvr {
  d: path("M13.264 21.733V16.26l5.528.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.qtbbj-y7w {
  stop-color: var(--svg-color--cb8139, #CB8139);
}

.quxai4aum {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw90o_byh {
  stop-color: var(--svg-color--bc8531, #BC8531);
}

.r_t84mbpt {
  fill: var(--svg-color--ffda42, #FFDA42);
  d: path("m21.499 12.27l-3.145-1.206l-.136 2.175l3.578 1.368c.185.083.651.2 1.039 0s.515-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.038.494.276.836.437.961z");
}

.r3o1jnbex {
  stop-color: var(--svg-color--3391ee, #3391EE);
  stop-opacity: 0;
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rlgwf126s {
  stop-color: var(--svg-color--43abff, #43ABFF);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s2zpt4bdz {
  stop-color: var(--svg-color--d08154, #D08154);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.t0dfidbsh {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
  stop-opacity: 0;
}

.t16p7zajb {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.863-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.teavi7b3d {
  stop-color: var(--svg-color--3b9bf4, #3B9BF4);
  stop-opacity: 0;
}

.tn00ksbky {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.235-3.836z");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u2p7zvbzn {
  stop-color: var(--svg-color--2851b6, #2851B6);
  stop-opacity: 0;
}

.u5zvm6bcl {
  d: path("M16.017 10.71a24 24 0 0 0-1.985.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a24 24 0 0 0-1.985-.163h-.027");
}

.uad7v8byj {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.903 7.838l-.36.748c-.045.154.062.308.214.308h.324c.152 0 .26-.157.215-.308l-.22-.748c-.046-.165-.124-.165-.173 0");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.uin7i86hm {
  stop-color: var(--svg-color--ffc337, #FFC337);
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utbg4t6zg {
  fill: var(--svg-color--000, #000);
  d: path("M15.288 7.775c0-.125-.1-.225-.225-.225a.224.224 0 0 0-.2.328h.398a.2.2 0 0 0 .027-.103");
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uvyxh01-z {
  stop-color: var(--svg-color--2851b6, #2851B6);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7sz3oo0t {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.129c.1.103.144.418-.094.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.vj70_lxns {
  stop-color: var(--svg-color--ffc337, #FFC337);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
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

.w2mg53b0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .284.31L20.5 11.24l.84.086a.21.21 0 0 1-.043.418l-1.21-.124l-.955.875a.21.21 0 1 1-.284-.31z");
}

.waah2bcle {
  stop-color: var(--svg-color--3968ab, #3968AB);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wke8dtqov {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .216-.373l.054-.894z");
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wte04qb6c {
  cx: 14.944px;
  cy: 7.55px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.171px;
  ry: 0.087px;
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xnu-7l9ks {
  stop-color: var(--svg-color--fcb63b, #FCB63B);
}

.xsno6rw2t {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
  stop-opacity: 0;
}

.xxjj5obiq {
  stop-color: var(--svg-color--4db6ff, #4DB6FF);
}

.y39x50mqx {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
}

.y9drs-b-r {
  stop-color: var(--svg-color--e79b27, #E79B27);
  stop-opacity: 0;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yn_cprukr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.025-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .283-.312l-4.235-3.836z");
}

.yv86un7fh {
  stop-color: var(--svg-color--ffdb3e, #FFDB3E);
  stop-opacity: 0;
}

.ywk-_ln5y {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
}

.yx_6dvgle {
  d: path("M15.063 7.382a.392.392 0 0 0-.378.496h.758a.395.395 0 0 0-.38-.496");
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

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z71en7xch {
  fill: var(--svg-color--000, #000);
  d: path("M16.759 7.775c0-.125.1-.225.225-.225a.224.224 0 0 1 .2.328h-.398a.2.2 0 0 1-.027-.103");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
