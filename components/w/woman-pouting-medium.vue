<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iR64Lnd)"><path fill="url(#iOxzlZc)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#iUn6BCu)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#iRhCTid)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#i4ivPUb)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#itc2YJb)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#i1vg3fd)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#iEccQsc)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#iX6t80N)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#ioLDcJJ)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#iRcMZ0s)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#iUNPFsc)" clip-rule="evenodd" class="dn9bcybwl"/><path fill="url(#idFJxab)" clip-rule="evenodd" class="dn9bcybwl"/></g><path fill="url(#iqkbJ5b)" class="nbb4y2b5h"/><path fill="url(#iFkR15T)" class="nbb4y2b5h"/><path fill="url(#iXXCYgd)" class="nbb4y2b5h"/><path fill="url(#i7oXz9d)" class="nbb4y2b5h"/><path fill="url(#idyVLJc)" class="xxbt6zn9m"/><path fill="url(#i1h68Ic)" class="xxbt6zn9m"/><path fill="url(#i9dtpAb)" class="ldghddv0u"/><path fill="url(#iWw9U4c)" class="ldghddv0u"/><path fill="url(#iBODEdK)" class="ldghddv0u"/><g filter="url(#iExx4eb)"><path fill="url(#iLDDhid)" class="en7s-n43f"/><path fill="url(#ilBTudb)" class="en7s-n43f"/></g><path fill="url(#iDvaDUc)" class="en7s-n43f"/><path fill="url(#ifkNrle)" class="en7s-n43f"/><path fill="url(#iIKFvze)" class="en7s-n43f"/><g filter="url(#i0Jpkse)"><path fill="url(#inI2Qcb)" class="drrtrhbzn"/><path fill="url(#iTniepe)" class="drrtrhbzn"/></g><rect fill="url(#iL82Lpe)" class="dn4d3682r"/><g filter="url(#iwbyWpd)"><path fill="url(#iZBhLAc)" class="ak-jp07-j"/></g><path fill="url(#imbpXEb)" class="ak-jp07-j"/><g filter="url(#i5bM9kd)"><path fill="url(#if2m0hd)" class="fg8vny28n"/><path fill="url(#iSuk5ib)" class="fg8vny28n"/></g><g filter="url(#iFgTKsb)"><path class="m_rczccbm"/><path fill="url(#ihR6G5d)" class="ewlqpzbam"/></g><g filter="url(#ibo6Q9d)"><path class="ihzxn7wsm"/><path fill="url(#iAAIpab)" class="g1xltsbmg"/></g><g filter="url(#iFr97MW)"><path fill="url(#iJDrKcc)" class="tipi-fbir"/><path fill="url(#i1WszvE)" class="tipi-fbir"/><path fill="url(#ih4QLie)" class="tipi-fbir"/><path fill="url(#iA20bPb)" class="tipi-fbir"/><path fill="url(#iQb6sEc)" class="tipi-fbir"/><path fill="url(#ivI8nKZ)" class="tipi-fbir"/><path fill="url(#ipRq7Zc)" class="tipi-fbir"/><path fill="url(#ihTFjuc)" class="tipi-fbir"/><path fill="url(#iyzZaFc)" class="tipi-fbir"/></g><path fill="url(#ixNokOS)" class="tipi-fbir"/><g filter="url(#i0Q6BBd)"><path class="o-l6z2bfk"/></g><g filter="url(#inP8Tpe)"><path class="pvz61iugy"/><path fill="url(#imnSPcb)" class="ubfqgnb4x"/><path fill="url(#iG3kafb)" class="ubfqgnb4x"/><path fill="url(#i09mCMh)" class="ubfqgnb4x"/><path fill="url(#iW2Zkrb)" class="ubfqgnb4x"/></g><path fill="url(#iXWivVD)" class="ubfqgnb4x"/><path fill="url(#iV1Rarb)" class="ubfqgnb4x"/><g filter="url(#iO1HaOc)"><path class="tiu3w3lbw"/></g><g filter="url(#iEsnvPe)"><path class="jbc4-sbke"/></g><path class="x_ano49uj"/><path fill="url(#i17rMWE)" class="sdhv44bmj"/><path class="tpak3rfas"/><g filter="url(#ignPafe)"><path class="fgaumob6c"/><path fill="url(#iAXaAgH)" class="gevluxbmh"/></g><g filter="url(#ik9do0c)"><path fill="url(#inBLGdO)" class="ttulilyqm"/></g><path class="msv-libsl"/><path fill="url(#iqV1nEd)" class="dg5gambfb"/><path class="kni6k4bkm"/><g filter="url(#iybhYed)"><path fill="url(#i5wAjdb)" class="k1v19jupi"/></g><g filter="url(#iQn4Gub)"><ellipse transform="rotate(-27.914 13.504 10.093)" class="zg32js-qv"/><ellipse fill="url(#iuB6Ate)" transform="rotate(-27.914 13.504 10.093)" class="gdbd5qylj"/></g><g filter="url(#ii8wjbd)"><path class="rf_8f4btf"/><path fill="url(#i1jQLGd)" class="uoh6k-q-t"/><path fill="url(#ifns9ge)" class="uoh6k-q-t"/></g><g filter="url(#iRwthPd)"><path class="p33jd1bag"/><path fill="url(#iloa5wc)" class="b3i-fdcqk"/><path fill="url(#iXCRqtb)" class="b3i-fdcqk"/></g><g filter="url(#iI3aFmc)"><path stroke="url(#iaW0vUb)" class="ky4jakchu"/></g><g filter="url(#i08D0ac)"><path class="qn5vhxb2v"/></g><g filter="url(#ig2Pysd)"><path stroke="url(#iFQDdJd)" clip-rule="evenodd" class="et0ldf7oc"/><path stroke="url(#iMJBAdc)" clip-rule="evenodd" class="et0ldf7oc"/></g><path clip-rule="evenodd" class="q5b4z1bji"/><g filter="url(#iDopDYc)"><path fill="url(#iBITCFb)" class="kexj4gomu"/></g><g filter="url(#igf7GNd)"><rect class="dwvhfuu8y"/></g><g filter="url(#ig8CQhc)"><rect class="irkgmj_gm"/></g><g filter="url(#iqZy0Jb)"><path class="e2exv7dmc"/></g><g filter="url(#iRGI1fd)"><path class="d57arlbyl"/></g><defs><radialGradient id="iUn6BCu" cx="0" cy="0" r="1" gradientTransform="matrix(-.61436 4.64187 -5.79864 -.76746 15.694 13.344)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iRhCTid" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.332 8.77)scale(3.54054 4.65199)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="i4ivPUb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.811 8.247)scale(2.19133 1.68264)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="itc2YJb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.253 7.712)scale(2.52001 1.77513)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="i1vg3fd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39937 2.66225 -3.69562 1.94255 12.418 2.592)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iEccQsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46756 1.46766 -2.05103 -2.0509 21.94 4.709)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iX6t80N" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87715 .5461 -1.13886 -3.91463 23.647 9.931)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="ioLDcJJ" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.69 8.124)scale(2.9552 3.76448)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iRcMZ0s" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.076 -3.72)scale(2.8512 2.25513)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iUNPFsc" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -89.71 98.135)scale(1.53963 2.49465)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="idFJxab" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.291 -3.857)scale(3.86684 1.39562)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iqkbJ5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.625 -11.8762 0 16.002 15.958)" gradientUnits="userSpaceOnUse"><stop class="l4nwu-c5t"/><stop offset="1" class="c0giurt9j"/></radialGradient><radialGradient id="iFkR15T" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.06339 5.05408 0 22.943 23.27)" gradientUnits="userSpaceOnUse"><stop class="kropdjn8m"/><stop offset="1" class="jl9qoxtbg"/></radialGradient><radialGradient id="i7oXz9d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65625 0 0 -3.18983 15.005 15.49)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="vpya669ti"/><stop offset="1" class="sh_b6m3le"/></radialGradient><radialGradient id="idyVLJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4266 -.1154 .41566 5.13875 24.387 23.762)" gradientUnits="userSpaceOnUse"><stop class="cp-d4w76k"/><stop offset="1" class="kbv5awe4z"/></radialGradient><radialGradient id="i9dtpAb" cx="0" cy="0" r="1" gradientTransform="matrix(3.29142 1.0992 -1.85676 5.55982 5.897 21.547)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="czk58ibbt"/><stop offset=".965" class="j_bmu-wtk"/></radialGradient><radialGradient id="iBODEdK" cx="0" cy="0" r="1" gradientTransform="matrix(.17189 -4.40625 .36187 .01412 8.552 24.58)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="jw1a1w0ab"/><stop offset="1" class="b462b5bvz"/></radialGradient><radialGradient id="iLDDhid" cx="0" cy="0" r="1" gradientTransform="matrix(14.39625 1.34665 -.12277 1.31245 16.667 24.736)" gradientUnits="userSpaceOnUse"><stop class="yah900b0p"/><stop offset="1" class="j_ok42bcu"/></radialGradient><radialGradient id="iDvaDUc" cx="0" cy="0" r="1" gradientTransform="matrix(.53911 1.07078 -4.30786 2.16889 17.493 26.514)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="sk5rjjbho"/><stop offset="1" class="s0nuiabwf"/></radialGradient><radialGradient id="ifkNrle" cx="0" cy="0" r="1" gradientTransform="rotate(163.022 11.216 13.965)scale(5.74064 1.49909)" gradientUnits="userSpaceOnUse"><stop class="gc1g17bro"/><stop offset="1" class="it3dq1b0b"/></radialGradient><radialGradient id="iIKFvze" cx="0" cy="0" r="1" gradientTransform="rotate(-134.178 11.952 9.583)scale(4.61877 12.7797)" gradientUnits="userSpaceOnUse"><stop class="j7z7erb3l"/><stop offset="1" class="wpvz2t1ix"/></radialGradient><radialGradient id="inI2Qcb" cx="0" cy="0" r="1" gradientTransform="matrix(.53055 2.37442 -20.91953 4.67434 16.283 25.396)" gradientUnits="userSpaceOnUse"><stop offset=".044" class="p0awsabvp"/><stop offset=".498" class="yvdkubc_i"/></radialGradient><radialGradient id="iL82Lpe" cx="0" cy="0" r="1" gradientTransform="matrix(2.62845 2.05877 -2.5322 3.2329 15.47 16.552)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="o1mi4hbsy"/><stop offset=".962" class="wya49db3a"/></radialGradient><radialGradient id="imbpXEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.66557 -1.22532 1.38845 -.75418 10.83 12.436)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="if2m0hd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 36.014 -40.808)scale(2.78378 3.39886)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iSuk5ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.22873 0 0 .52904 21.036 9.06)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ihR6G5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.53731 -.11435 .0894 1.20175 20.473 10.912)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iAAIpab" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.659 5.399)scale(1.07514)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iJDrKcc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.62169 3.05348 -4.08703 -8.86301 18.913 10.25)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i1WszvE" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.835 7.454)scale(2.42529 1.68893)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="ih4QLie" cx="0" cy="0" r="1" gradientTransform="matrix(1.31256 -3.9997 5.07488 1.6654 13.8 16.876)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iA20bPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30804 7.50709 -9.38377 -1.63503 17.043 9.828)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ndb61xwjr"/><stop offset="1" class="l57p2o49o"/></radialGradient><radialGradient id="iQb6sEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38256 -6.41674 0 15.734 10.646)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="i-c7amj6z"/><stop offset="1" class="nmcs74byh"/></radialGradient><radialGradient id="ivI8nKZ" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.339 6.874)scale(7.16519 12.3363)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="ipRq7Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17167 1.43796 0 18.345 9.825)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="ihTFjuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.33635 1.53155 0 13.887 9.592)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iyzZaFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.88596 3.28535 -2.62882 -.70892 17.41 7.467)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="ixNokOS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30862 0 0 -6.56263 21.19 11.34)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="imnSPcb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46382 -2.08113 .64138 -.14294 16.8 12.079)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iW2Zkrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79356 0 0 -.22185 16.556 12.295)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iV1Rarb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39611 .95848 -1.15195 -1.67791 16.386 11.689)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="i17rMWE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82605 -1.31393 0 18.224 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iAXaAgH" cx="0" cy="0" r="1" gradientTransform="matrix(-.23613 -.30428 .41893 -.3251 17.991 10.276)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqV1nEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82605 -1.31393 0 13.78 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iuB6Ate" cx="0" cy="0" r="1" gradientTransform="matrix(-.00788 -.50303 .60467 -.00947 13.489 10.413)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1jQLGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28495 -2.80547 1.4352 .65735 10.24 8.031)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ifns9ge" cx="0" cy="0" r="1" gradientTransform="rotate(-59.802 12.105 -6.9)scale(2.32689 1.24922)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iloa5wc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1503 4.4712 -7.31016 -3.51563 17.947 2.73)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iXCRqtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21415 1.39202 -2.99487 -.46074 16.216 3.106)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iFQDdJd" cx="0" cy="0" r="1" gradientTransform="rotate(116.896 4.003 12.163)scale(.30222 .93391)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zx0m_lbus"/><stop offset="1" class="ry9rm1byo"/></radialGradient><radialGradient id="iMJBAdc" cx="0" cy="0" r="1" gradientTransform="matrix(.16016 -.09766 .11816 .19379 14.927 14.22)" gradientUnits="userSpaceOnUse"><stop class="zx0m_lbus"/><stop offset="1" class="ry9rm1byo"/></radialGradient><radialGradient id="iBITCFb" cx="0" cy="0" r="1" gradientTransform="matrix(.55246 -.30628 .24334 .43892 15.83 14.931)" gradientUnits="userSpaceOnUse"><stop class="uk64kwb3f"/><stop offset="1" class="gm73dgbyl"/></radialGradient><filter id="iR64Lnd" width="15.541" height="16.041" x="8.356" y="1.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="iExx4eb" width="19.161" height="7.244" x="8.163" y="22.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.352941 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="i0Jpkse" width="19.009" height="7.177" x="5.176" y="22.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.415686 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="iwbyWpd" width="3.427" height="3.277" x="9.593" y="9.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="i5bM9kd" width="3.277" height="3.527" x="19.278" y="8.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="iFgTKsb" width="3.187" height="3.187" x="19.323" y="9.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".25"/></filter><filter id="ibo6Q9d" width="2.887" height="2.887" x="9.807" y="9.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".175"/></filter><filter id="iFr97MW" width="10.376" height="11.474" x="10.814" y="5.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="i0Q6BBd" width="2.911" height="3.731" x="14.381" y="9.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".25"/></filter><filter id="inP8Tpe" width="2.411" height="3.231" x="14.796" y="9.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".125"/></filter><filter id="iO1HaOc" width="2.952" height="1.309" x="17.065" y="9.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="iEsnvPe" width="2.952" height="1.309" x="11.987" y="9.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="ignPafe" width=".797" height=".705" x="17.478" y="9.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".05"/></filter><filter id="ik9do0c" width=".9" height=".923" x="18.335" y="9.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".1"/></filter><filter id="iybhYed" width=".997" height="1.052" x="13.811" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".1"/></filter><filter id="iQn4Gub" width=".926" height=".714" x="13.041" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".05"/></filter><filter id="ii8wjbd" width="4.474" height="4.781" x="9.439" y="3.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/><feGaussianBlur result="effect2_foregroundBlur_13036_4640" stdDeviation=".25"/></filter><filter id="iRwthPd" width="8.917" height="5.878" x="12.779" y="2.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/><feGaussianBlur result="effect2_foregroundBlur_13036_4640" stdDeviation=".125"/></filter><filter id="iI3aFmc" width="1.155" height="2.341" x="12.758" y="3.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".1"/></filter><filter id="i08D0ac" width="7.017" height="3.906" x="15.173" y="4.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".5"/></filter><filter id="ig2Pysd" width="2.698" height="1.082" x="14.766" y="13.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".05"/></filter><filter id="iDopDYc" width="1.224" height=".712" x="15.456" y="14.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".05"/></filter><filter id="igf7GNd" width="2.848" height=".741" x="12.531" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.12549 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="ig8CQhc" width="2.848" height=".741" x="17.05" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.12549 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4640"/></filter><filter id="iqZy0Jb" width="2.62" height=".55" x="17.123" y="8.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".075"/></filter><filter id="iRGI1fd" width="2.62" height=".55" x="12.628" y="8.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4640" stdDeviation=".075"/></filter><linearGradient id="iOxzlZc" x1="20.78" x2="14.534" y1="3.719" y2="14.675" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iXXCYgd" x1="16.505" x2="16.505" y1="30.331" y2="26.581" gradientUnits="userSpaceOnUse"><stop class="waift8brn"/><stop offset="1" class="qeur-ccno"/></linearGradient><linearGradient id="i1h68Ic" x1="22.8" x2="23.56" y1="22.828" y2="22.774" gradientUnits="userSpaceOnUse"><stop class="cyj659bzg"/><stop offset="1" class="jmgn8ibxu"/></linearGradient><linearGradient id="iWw9U4c" x1="9.63" x2="8.474" y1="23.831" y2="23.737" gradientUnits="userSpaceOnUse"><stop class="g27c6tbna"/><stop offset="1" class="jvn9nabmr"/></linearGradient><linearGradient id="ilBTudb" x1="17.493" x2="17.493" y1="29.885" y2="25.771" gradientUnits="userSpaceOnUse"><stop class="e9t1eesnj"/><stop offset="1" class="pbdj5nq2i"/></linearGradient><linearGradient id="iTniepe" x1="16.658" x2="16.189" y1="28.302" y2="24.865" gradientUnits="userSpaceOnUse"><stop class="qe7ygsbdr"/><stop offset="1" class="ffeha75rt"/></linearGradient><linearGradient id="iZBhLAc" x1="9.593" x2="11.484" y1="10.887" y2="10.887" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iG3kafb" x1="15.046" x2="16.002" y1="12.153" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i09mCMh" x1="16.002" x2="16.002" y1="12.873" y2="12.235" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iXWivVD" x1="16.081" x2="16.081" y1="12.94" y2="12.798" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="inBLGdO" x1="19.015" x2="18.696" y1="10.245" y2="10.442" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5wAjdb" x1="14.537" x2="14.218" y1="10.245" y2="10.442" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaW0vUb" x1="12.837" x2="13.335" y1="3.719" y2="5.008" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pouting-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ak-jp07-j {
  d: path("M11.231 12.436a1.638 1.638 0 1 0 0-3.276a1.638 1.638 0 0 0 0 3.276");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b3i-fdcqk {
  d: path("M15.388 2.866c-1.154-.255-2.19.896-2.309 1.323c1.071 3.609 3.78 3.411 6.456 3.114c1.6-.178 1.774.552 1.91.904c0-4.004-3.404-4.755-6.028-5.335z");
}

.b462b5bvz {
  stop-color: var(--svg-color--685390, #685390);
  stop-opacity: 0;
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.c0giurt9j {
  stop-color: var(--svg-color--7c60b2, #7C60B2);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp-d4w76k {
  stop-color: var(--svg-color--a285de, #A285DE);
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.czk58ibbt {
  stop-color: var(--svg-color--81649d, #81649D);
}

.d57arlbyl {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.903 8.604h2.07");
}

.dg5gambfb {
  d: path("M13.778 9.704a.91.91 0 0 0-.876 1.149h1.756a1 1 0 0 0 .033-.24a.915.915 0 0 0-.913-.909");
}

.dn4d3682r {
  width: 4.223px;
  height: 6.028px;
  x: 13.876px;
  y: 12.584px;
  rx: 2.111px;
}

.dn9bcybwl {
  fill-rule: evenodd;
  d: path("M23.317 12.233c.217-.443.33-.937.33-1.453c0-.475-.098-.922-.273-1.329h.005a3.3 3.3 0 0 0-.286-.522l-.002-.003a3.3 3.3 0 0 1-.536-1.803v-.01a3.36 3.36 0 0 0-3.36-3.36a.55.55 0 0 1-.463-.237a3.37 3.37 0 0 0-2.73-1.401a3.37 3.37 0 0 0-2.731 1.401a.58.58 0 0 1-.464.237l-.086.001a3.36 3.36 0 0 0-3.273 3.358v.01c0 .64-.185 1.268-.536 1.804l-.002.004a3.36 3.36 0 0 0-.224 3.303a.52.52 0 0 1 0 .464a3.272 3.272 0 0 0 2.947 4.709h8.738a3.27 3.27 0 0 0 3.276-3.277c0-.515-.124-1-.33-1.432a.52.52 0 0 1 0-.464m-12.482-2.72h-.013l1.22 2.398c.126 2.853 1.24 0 3.96 0s3.906 3.176 4.031.322l1.157-3.255c-.055-1.267-.974-1.356-1.157-1.356h-3.278a3.93 3.93 0 0 1-3.247-1.704a.269.269 0 0 0-.47.052l-.084.197a2.35 2.35 0 0 1-1.211 1.257l-.052.021q-.029.013-.053.02c-.24.126-.803.5-.824 1.466l.01.311z");
}

.drrtrhbzn {
  d: path("M5.626 28.427c-.6-1.05-.454-2.813-.375-3.598l3.937-.168c.413.213 1.526.089 2.031 0l9.672-1.562c.617-.118 1.448-.177 2.125.187c.728.392.7.965.642 1.352a.1.1 0 0 1-.063.078c-4.286 1.54-12.404 4.813-13.524 5.062c-1.82.313-3.695-.039-4.445-1.351");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dwvhfuu8y {
  width: 2.648px;
  height: 0.541px;
  x: 12.531px;
  y: 8.38px;
  fill: var(--svg-color--452c2a, #452C2A);
  rx: 0.271px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2exv7dmc {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.398 8.604h2.07");
}

.e9t1eesnj {
  stop-color: var(--svg-color--a16679, #A16679);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.en7s-n43f {
  d: path("M26.374 28.427c.6-1.05.454-2.813.375-3.598l-3.937-.168c-.413.213-1.526.089-2.031 0l-8.898-1.406c-.617-.117-2.096-.232-2.773.133c-.766.412-1 1.192-.938 1.578c4.271 1.531 12.632 4.562 13.757 4.812c1.82.313 3.695-.039 4.445-1.351");
}

.et0ldf7oc {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.952 14.261a1.54 1.54 0 0 0-1.673 0a.2.2 0 0 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 1 1-.225.33");
}

.ewlqpzbam {
  d: path("M20.917 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.ffeha75rt {
  stop-color: var(--svg-color--a56b82, #A56B82);
  stop-opacity: 0;
}

.fg8vny28n {
  d: path("M20.917 12.436a1.638 1.638 0 1 0 0-3.276a1.638 1.638 0 0 0 0 3.276");
}

.fgaumob6c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.159 9.897c.065.086-.07.192-.225.307c-.154.115-.268.196-.332.11c-.065-.088.007-.25.161-.366s.331-.138.396-.051");
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g1xltsbmg {
  d: path("M11.25 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.g27c6tbna {
  stop-color: var(--svg-color--5f488a, #5F488A);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gc1g17bro {
  stop-color: var(--svg-color--aa8368, #AA8368);
}

.gdbd5qylj {
  cx: 13.504px;
  cy: 10.093px;
  rx: 0.397px;
  ry: 0.201px;
}

.gevluxbmh {
  d: path("M18.159 9.897c.065.086-.07.192-.225.307c-.154.115-.268.196-.332.11c-.065-.088.007-.25.161-.366s.331-.138.396-.051");
}

.gm73dgbyl {
  stop-color: var(--svg-color--834f4f, #834F4F);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-c7amj6z {
  stop-color: var(--svg-color--9f6394, #9F6394);
  stop-opacity: 0;
}

.ihzxn7wsm {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.25 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.irkgmj_gm {
  width: 2.648px;
  height: 0.541px;
  x: 17.05px;
  y: 8.38px;
  fill: var(--svg-color--452c2a, #452C2A);
  rx: 0.271px;
}

.it3dq1b0b {
  stop-color: var(--svg-color--aa8368, #AA8368);
  stop-opacity: 0;
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_bmu-wtk {
  stop-color: var(--svg-color--604885, #604885);
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j_ok42bcu {
  stop-color: var(--svg-color--c08f81, #C08F81);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j7z7erb3l {
  stop-color: var(--svg-color--8e6b57, #8E6B57);
}

.jbc4-sbke {
  fill: var(--svg-color--585759, #585759);
  d: path("M14.84 10.219c-.271-.476-.682-.851-1.566-.851c-.387 0-.76.107-1.092.375c-.274.222-.238.505-.026.61l.567.324c.663-.215 1.397-.244 2.116-.458");
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jl9qoxtbg {
  stop-color: var(--svg-color--9d80d7, #9D80D7);
  stop-opacity: 0;
}

.jmgn8ibxu {
  stop-color: var(--svg-color--7555ae, #7555AE);
  stop-opacity: 0;
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jvn9nabmr {
  stop-color: var(--svg-color--5f488a, #5F488A);
  stop-opacity: 0;
}

.jw1a1w0ab {
  stop-color: var(--svg-color--685390, #685390);
}

.k1v19jupi {
  d: path("M14.608 10.506c0-.293-.239-.49-.303-.548l-.294.284l.18.368z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kbv5awe4z {
  stop-color: var(--svg-color--8f74c8, #8F74C8);
}

.kexj4gomu {
  d: path("M16.58 14.931a.512.512 0 1 0-1.024 0z");
}

.kni6k4bkm {
  fill: var(--svg-color--000, #000);
  d: path("M14.298 10.613c0-.29-.23-.52-.52-.52a.518.518 0 0 0-.463.76h.921a.5.5 0 0 0 .062-.24");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kropdjn8m {
  stop-color: var(--svg-color--9d80d7, #9D80D7);
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.ky4jakchu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.058 4.137c.024.248.239 1.178.555 1.741");
}

.l4nwu-c5t {
  stop-color: var(--svg-color--7d5bb9, #7D5BB9);
}

.l57p2o49o {
  stop-color: var(--svg-color--97577d, #97577D);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldghddv0u {
  d: path("m5.251 24.829l3.847-.16l.059.182h.031v-7.108a10.5 10.5 0 0 0-3.937 7.086");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m_rczccbm {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.917 11.892a1.094 1.094 0 1 0 0-2.188a1.094 1.094 0 0 0 0 2.188");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.msv-libsl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.567 9.428c-.665 0-1.226.458-1.38 1.078a.28.28 0 0 0 .273.347h2.272c.145 0 .26-.133.231-.277a1.43 1.43 0 0 0-1.396-1.148");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.nbb4y2b5h {
  d: path("m9.157 24.646l-3.906.183c.578-5.253 5.03-9.34 10.437-9.34h.625c5.415 0 9.872 4.098 10.44 9.362l-4.378-.206v5.188H9.157z");
}

.ndb61xwjr {
  stop-color: var(--svg-color--97577d, #97577D);
  stop-opacity: 0;
}

.nmcs74byh {
  stop-color: var(--svg-color--9f6394, #9F6394);
}

.o-l6z2bfk {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.602 10.571l-.696 1.731a.55.55 0 0 0 .53.712h.8a.55.55 0 0 0 .53-.712l-.54-1.73c-.116-.384-.502-.384-.624 0");
}

.o1mi4hbsy {
  stop-color: var(--svg-color--815559, #815559);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p0awsabvp {
  stop-color: var(--svg-color--c99e8a, #C99E8A);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p33jd1bag {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.388 2.866c-1.154-.255-2.19.896-2.309 1.323c1.071 3.609 3.78 3.411 6.456 3.114c1.6-.178 1.774.552 1.91.904c0-4.004-3.404-4.755-6.028-5.335z");
}

.pbdj5nq2i {
  stop-color: var(--svg-color--a16679, #A16679);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvz61iugy {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.613 10.43l-.542 1.731a.55.55 0 0 0 .53.712h.801a.55.55 0 0 0 .53-.712l-.54-1.73c-.117-.384-.658-.384-.78 0");
}

.q5b4z1bji {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.952 14.261a1.54 1.54 0 0 0-1.673 0a.2.2 0 0 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 1 1-.225.33");
}

.qe7ygsbdr {
  stop-color: var(--svg-color--a56b82, #A56B82);
}

.qeur-ccno {
  stop-color: var(--svg-color--7150b0, #7150B0);
  stop-opacity: 0;
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qn5vhxb2v {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("M18.452 6.541L17 6.808a.7.7 0 1 1-.127-1.39h2.383c1.41 0 1.877 1.421 1.934 1.906a3.2 3.2 0 0 0-2.738-.783");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rf_8f4btf {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.84 4.701c.576-.61 1.667-.611 2.17-.52l.403 1.314c-.257-.04-.3-.002-.494.186c-.14 1.113-1.401 1.789-2.939 2.237c-.15-1.519.111-2.423.86-3.217");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.ry9rm1byo {
  stop-color: var(--svg-color--b48e84, #B48E84);
  stop-opacity: 0;
}

.s0nuiabwf {
  stop-color: var(--svg-color--834d6a, #834D6A);
  stop-opacity: 0;
}

.sdhv44bmj {
  d: path("M18.226 9.704a.91.91 0 0 1 .875 1.149h-1.755a.912.912 0 0 1 .88-1.148");
}

.sh_b6m3le {
  stop-color: var(--svg-color--482e57, #482E57);
  stop-opacity: 0;
}

.sk5rjjbho {
  stop-color: var(--svg-color--834d6a, #834D6A);
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tipi-fbir {
  d: path("M10.822 9.512h.013l-.01-.27l-.011-.311c.02-.966.584-1.34.825-1.465l.052-.02l.052-.022a2.34 2.34 0 0 0 1.211-1.257l.084-.197a.268.268 0 0 1 .47-.052a3.93 3.93 0 0 0 3.247 1.704h3.278c.183 0 1.102.089 1.157 1.356l-.121 3.129c-.126 2.853-2.354 4.77-5.074 4.77s-4.948-1.917-5.074-4.77z");
}

.tiu3w3lbw {
  fill: var(--svg-color--504f51, #504F51);
  d: path("M17.165 10.219c.27-.476.68-.851 1.565-.851c.387 0 .76.107 1.092.375c.274.222.237.505.025.61l-.566.324c-.664-.215-1.397-.244-2.116-.458");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tpak3rfas {
  fill: var(--svg-color--000, #000);
  d: path("M17.705 10.613c0-.29.231-.52.52-.52a.518.518 0 0 1 .463.76h-.921a.47.47 0 0 1-.062-.24");
}

.ttulilyqm {
  d: path("M19.035 10.493a.86.86 0 0 0-.236-.47l-.264.29l.12.232z");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ubfqgnb4x {
  d: path("m15.613 10.43l-.542 1.731a.55.55 0 0 0 .53.712h.801a.55.55 0 0 0 .53-.712l-.54-1.73c-.117-.384-.658-.384-.78 0");
}

.uk64kwb3f {
  stop-color: var(--svg-color--986e67, #986E67);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uoh6k-q-t {
  d: path("M10.84 4.701c.576-.61 1.667-.611 2.17-.52l.403 1.314c-.257-.04-.3-.002-.494.186c-.14 1.113-1.401 1.789-2.939 2.237c-.15-1.519.111-2.423.86-3.217");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vpya669ti {
  stop-color: var(--svg-color--482e57, #482E57);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.waift8brn {
  stop-color: var(--svg-color--7150b0, #7150B0);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wpvz2t1ix {
  stop-color: var(--svg-color--8e6b57, #8E6B57);
  stop-opacity: 0;
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wya49db3a {
  stop-color: var(--svg-color--b0867c, #B0867C);
}

.x_ano49uj {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.436 9.428c.665 0 1.227.458 1.38 1.078a.28.28 0 0 1-.273.347h-2.272a.234.234 0 0 1-.23-.277a1.42 1.42 0 0 1 1.395-1.148");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xxbt6zn9m {
  d: path("M22.925 17.832a10.48 10.48 0 0 1 3.827 7.02l-3.827-.18z");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yah900b0p {
  stop-color: var(--svg-color--ba9180, #BA9180);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yvdkubc_i {
  stop-color: var(--svg-color--a78170, #A78170);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zg32js-qv {
  cx: 13.504px;
  cy: 10.093px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.zx0m_lbus {
  stop-color: var(--svg-color--b48e84, #B48E84);
}

</style>
