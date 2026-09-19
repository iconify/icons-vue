<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i89nikd)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iIQaMif)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#i8eMFYd)"><path fill="url(#i5I72Pc)" class="pb1pwib-r"/><path fill="url(#iX1BTZW)" class="pb1pwib-r"/></g><g filter="url(#iNTRV1b)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#ipjWRwb)"><path class="g11vnob-s"/></g><g filter="url(#iioPAee)"><path class="yn_cprukr"/></g><g filter="url(#iOPPalb)"><path class="w2mg53b0k"/></g><g filter="url(#iuIqexe)"><path class="tn00ksbky"/></g><g filter="url(#iiDIDSb)"><rect class="muxg66bas"/><rect fill="url(#iDG4Gmd)" class="m0dkjhbrx"/></g><g filter="url(#iYXOO6d)"><path fill="url(#ioitlCc)" class="t16p7zajb"/></g><path fill="url(#i5Ao9Gd)" class="t16p7zajb"/><path fill="url(#i8KfH3d)" class="t16p7zajb"/><path fill="url(#iEdEbnd)" class="t16p7zajb"/><path class="n-gofxbqk"/><path fill="url(#iGgZmQl)" class="qqobt5tvr"/><path fill="url(#iVakvLc)" class="qqobt5tvr"/><path fill="url(#i3gy0Bb)" class="qqobt5tvr"/><path fill="url(#iuPT4Kc)" class="qqobt5tvr"/><path fill="url(#iHyYx2b)" class="qqobt5tvr"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><g filter="url(#icMBGCc)"><path fill="url(#icEqrcb)" class="fwk98bb0c"/><path fill="url(#i6NcB5w)" class="fwk98bb0c"/><path fill="url(#iOT1dbd)" class="fwk98bb0c"/></g><path fill="url(#iR15onA)" class="wke8dtqov"/><path fill="url(#iDv7Hjb)" class="wke8dtqov"/><g filter="url(#ipLSnDb)"><path class="oisgcibyz"/><path fill="url(#iDWZ8ed)" class="ajsjeuojy"/><path fill="url(#ioaS3Kb)" class="ajsjeuojy"/></g><path fill="url(#iFc3g8a)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle class="ar7i_ib9g"/><g filter="url(#iPLhr4b)"><path class="ly32g8bmi"/><path fill="url(#iUWKqhD)" class="k-27-x9ja"/></g><g filter="url(#icvhEGc)"><path class="vms7zebge"/><path fill="url(#iJKHnVb)" class="dixb6cljt"/><path fill="url(#iaLzn5A)" class="dixb6cljt"/></g><g filter="url(#iWKj7Gb)"><path class="jtrouob-f"/></g><path fill="url(#iFc0eqy)" class="u5zvm6bcl"/><path fill="url(#iZeEFzX)" class="u5zvm6bcl"/><path fill="url(#i7zEfhH)" class="u5zvm6bcl"/><path fill="url(#iVRHTBe)" class="u5zvm6bcl"/><path fill="url(#iK804bd)" class="u5zvm6bcl"/><path fill="url(#iaW1cmd)" class="u5zvm6bcl"/><path fill="url(#iqcIBfc)" class="u5zvm6bcl"/><path fill="url(#inywS4e)" class="gdfj27b8p"/><path fill="url(#iam9OGk)" class="gdfj27b8p"/><g filter="url(#i1Lbkge)"><path stroke="url(#iT64Wjd)" class="saunobcmg"/></g><g filter="url(#iZlX6Wf)"><path stroke="url(#is2IIbG)" class="ikgkim2qs"/></g><g filter="url(#i1ltSMe)"><path stroke="url(#ipVew1d)" class="zh46g387g"/></g><g filter="url(#iJJj52d)"><circle fill="url(#i1fWkje)" class="kpd4qxbil"/></g><g filter="url(#iLQtPxe)"><circle fill="url(#i4P74Ce)" class="yatrv-bpo"/></g><g filter="url(#iGkt5Sd)"><circle fill="url(#iK1xdoe)" class="l5nncxbgw"/><circle fill="url(#iR7ewCc)" class="l5nncxbgw"/></g><g filter="url(#iKWUWmU)"><circle class="h5h3n5mvw"/><circle fill="url(#iBRYhIb)" class="z750v9bmx"/><circle fill="url(#iOCTDtd)" class="z750v9bmx"/></g><g filter="url(#iGsUJyc)"><path fill="url(#imbyLKc)" class="s7kqzl5sm"/><path fill="url(#iP2r41d)" class="s7kqzl5sm"/><path fill="url(#iwcUm1d)" class="s7kqzl5sm"/><path fill="url(#ix03fud)" class="s7kqzl5sm"/><path fill="url(#iO02K8E)" class="s7kqzl5sm"/></g><g filter="url(#ib4tthb)"><path fill="url(#iRqmCUc)" class="s545islfz"/></g><g filter="url(#iY0K6Xd)"><path class="mz44h-bzv"/><path fill="url(#iRu5UZb)" class="xfs4fx4gd"/><path fill="url(#idjvzTd)" class="xfs4fx4gd"/><path fill="url(#iYdieyd)" class="xfs4fx4gd"/><path fill="url(#iMSSZIb)" class="xfs4fx4gd"/></g><g filter="url(#i2PN9Ul)"><path class="agbclbc9u"/></g><g filter="url(#iqqQjee)"><path class="fq5b1gb4r"/><path fill="url(#iaS389d)" class="n6_mbsb0e"/><path fill="url(#itjKSgb)" class="n6_mbsb0e"/><path fill="url(#iALGF6c)" class="n6_mbsb0e"/><path fill="url(#iqWXzXd)" class="n6_mbsb0e"/></g><g filter="url(#iySxaDd)"><path stroke="url(#io5fovd)" class="qpfi3-_om"/></g><path class="is1z44opp"/><g filter="url(#idGkJSd)"><path class="uqdhtogep"/></g><g filter="url(#iNLQzSb)"><path class="nr39ys81r"/></g><path class="bvr_w2nyb"/><path fill="url(#iQkKA3b)" class="hd2qg8bsb"/><path class="j5n991bkm"/><g filter="url(#id1zeYb)"><path class="ksyyunbhv"/><path fill="url(#i0P4JvV)" class="m3w1habwo"/></g><g filter="url(#iEUHAMe)"><path fill="url(#ijBggGe)" class="i8qnejbvt"/></g><path class="dpqo2gbuc"/><path fill="url(#iu8u6rd)" class="oreqjlb-y"/><path class="wj6ixej_e"/><g filter="url(#iEJx8Bd)"><path fill="url(#i9Rc3fd)" class="nzqb2mw4u"/></g><g filter="url(#ir2JOSg)"><ellipse transform="rotate(-27.914 14.936 7.594)" class="e96vxibaa"/><ellipse fill="url(#iodryid)" transform="rotate(-27.914 14.936 7.594)" class="krisv8b8a"/></g><g filter="url(#ixNASJT)"><path stroke="url(#iPUPF1d)" class="bm7tflbxn"/></g><g filter="url(#ic1uQyQ)"><path stroke="url(#ib8vdcb)" class="q26bd-bbw"/></g><g filter="url(#iMsnqyb)"><path stroke="url(#iUBMbed)" class="dujjp1bsn"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iVakvLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68754 -5.0625 2.53124 -.34377 16.78 21.98)" gradientUnits="userSpaceOnUse"><stop class="uvyxh01-z"/><stop offset="1" class="u2p7zvbzn"/></radialGradient><radialGradient id="i3gy0Bb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.125 15.9 2.484)scale(.88884 .66004)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="kcor2lvvo"/><stop offset="1" class="t0dfidbsh"/></radialGradient><radialGradient id="iHyYx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 -4.56052 .72812 .03493 14.75 21.79)" gradientUnits="userSpaceOnUse"><stop class="ywk-_ln5y"/><stop offset="1" class="quxai4aum"/></radialGradient><radialGradient id="iOT1dbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17187 2.9198 -.50904 -.02996 15.382 25.78)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="zx20zqh8j"/><stop offset="1" class="j807r45wk"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="ioaS3Kb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="uz8dj8b7c"/><stop offset="1" class="z5e-1sbyl"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iUWKqhD" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.302)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="lh4nfkb5q"/><stop offset="1" class="zz3980hzg"/></radialGradient><radialGradient id="iJKHnVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="ev6-__b2a"/><stop offset="1" class="rsfgarwma"/></radialGradient><radialGradient id="iaLzn5A" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="asecgoboj"/><stop offset=".986" class="e5m3cbc6k"/></radialGradient><radialGradient id="i7zEfhH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.194 10.709)" gradientUnits="userSpaceOnUse"><stop class="ptfvfcbrt"/><stop offset="1" class="c9v8_hpvm"/></radialGradient><radialGradient id="iVRHTBe" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.147 8.847)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="y39x50mqx"/><stop offset="1" class="gmn2w47zp"/></radialGradient><radialGradient id="iK804bd" cx="0" cy="0" r="1" gradientTransform="matrix(1.67188 0 0 .4274 16.843 10.709)" gradientUnits="userSpaceOnUse"><stop class="nkm4r8_8f"/><stop offset="1" class="e2kf81bwk"/></radialGradient><radialGradient id="inywS4e" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="qlvkqabeg"/><stop offset="1" class="o9iemhbma"/></radialGradient><radialGradient id="iam9OGk" cx="0" cy="0" r="1" gradientTransform="rotate(160.1 7.47 6.92)scale(.87221 .42588)" gradientUnits="userSpaceOnUse"><stop class="u66aotmpr"/><stop offset="1" class="dqp3b0bfm"/></radialGradient><radialGradient id="i1fWkje" cx="0" cy="0" r="1" gradientTransform="matrix(.76116 0 0 1.33204 13.217 7.931)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iR7ewCc" cx="0" cy="0" r="1" gradientTransform="matrix(.35858 -.2611 .29801 .40927 18.23 7.816)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iBRYhIb" cx="0" cy="0" r="1" gradientTransform="matrix(.35622 -.65518 .38348 .2085 18.05 8.287)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iOCTDtd" cx="0" cy="0" r="1" gradientTransform="matrix(.11247 .11132 -.1435 .14499 18.067 7.93)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iwcUm1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.08182 -4.18341 0 15.87 7.845)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset=".931" class="uz8kaou5q"/></radialGradient><radialGradient id="ix03fud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56694 .69777 0 17.018 7.38)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iO02K8E" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60328 .75023 0 15.041 7.365)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iRu5UZb" cx="0" cy="0" r="1" gradientTransform="matrix(.34605 -1.28242 .47556 .12833 17.885 6.151)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="idjvzTd" cx="0" cy="0" r="1" gradientTransform="matrix(1.659 .15267 -.08209 .89203 17.173 5.387)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iYdieyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72833 -1.12798 0 16 4.2)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iMSSZIb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 17.54 -16.599)scale(1.653 2.5897)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iqWXzXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0854 -.27438 0 16.143 8.628)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iQkKA3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35182 -.55961 0 16.946 7.635)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0P4JvV" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 10.302 -.29)scale(.16404 .22585)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iu8u6rd" cx="0" cy="0" r="1" gradientTransform="scale(.55964 .35184)rotate(90 2.6 24.3)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iodryid" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21426 .25755 -.00403 14.93 7.73)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i89nikd" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1146" result="effect2_innerShadow_4002_1146"/></filter><filter id="iIQaMif" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1146" result="effect2_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1146" result="effect3_innerShadow_4002_1146"/></filter><filter id="i8eMFYd" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1146" result="effect2_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1146" result="effect3_innerShadow_4002_1146"/></filter><filter id="iNTRV1b" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="ipjWRwb" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1146" result="effect2_dropShadow_4002_1146"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1146" result="shape"/></filter><filter id="iioPAee" width="6.45" height="6.548" x="9.619" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1146" result="effect2_dropShadow_4002_1146"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1146" result="shape"/></filter><filter id="iOPPalb" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1146" result="effect2_dropShadow_4002_1146"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1146" result="shape"/></filter><filter id="iuIqexe" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1146" result="effect2_dropShadow_4002_1146"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1146" result="shape"/></filter><filter id="iiDIDSb" width="1.003" height="4.833" x="22.34" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="iYXOO6d" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="icMBGCc" width="2.97" height="8.306" x="13.261" y="21.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.262745 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="ipLSnDb" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="iPLhr4b" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.188235 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1146" result="effect2_innerShadow_4002_1146"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.188235 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1146" result="effect3_innerShadow_4002_1146"/></filter><filter id="icvhEGc" width="1.692" height="1.561" x="6.723" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.211765 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="iWKj7Gb" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.121569 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="i1Lbkge" width="4.609" height="5.161" x="19.13" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".25"/></filter><filter id="iZlX6Wf" width="1.248" height="2.077" x="21.759" y="8.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".1"/></filter><filter id="i1ltSMe" width=".822" height="1.445" x="22.798" y="8.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".1"/></filter><filter id="iJJj52d" width="1.648" height="1.448" x="13.217" y="7.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="iLQtPxe" width="1.863" height="1.863" x="13.01" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".25"/></filter><filter id="iGkt5Sd" width="1.698" height="1.698" x="17.344" y="6.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="iKWUWmU" width="1.863" height="1.863" x="17.136" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".25"/></filter><filter id="iGsUJyc" width="4.5" height="5.267" x="13.764" y="5.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="ib4tthb" width="3.842" height="3.33" x="15.075" y="4.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".5"/></filter><filter id="iY0K6Xd" width="5.466" height="3.589" x="13.268" y="4.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="i2PN9Ul" width="2.263" height="2.663" x="14.765" y="7.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".375"/></filter><filter id="iqqQjee" width=".914" height="1.263" x="15.544" y="7.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".025"/></filter><filter id="iySxaDd" width="1.596" height=".665" x="15.203" y="9.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".025"/></filter><filter id="idGkJSd" width="1.434" height="1.039" x="16.514" y="6.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="iNLQzSb" width="1.434" height="1.039" x="14.281" y="6.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1146"/></filter><filter id="id1zeYb" width=".454" height=".415" x="16.571" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".05"/></filter><filter id="iEUHAMe" width=".613" height=".623" x="16.878" y="7.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".1"/></filter><filter id="iEJx8Bd" width=".654" height=".678" x="14.952" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".1"/></filter><filter id="ir2JOSg" width=".509" height=".419" x="14.681" y="7.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".05"/></filter><filter id="ixNASJT" width="1.252" height=".637" x="16.496" y="6.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".075"/></filter><filter id="ic1uQyQ" width="1.386" height=".762" x="14.182" y="6.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".075"/></filter><filter id="iMsnqyb" width=".862" height="1.409" x="13.548" y="5.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1146" stdDeviation=".125"/></filter><linearGradient id="i5I72Pc" x1="8.528" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iDG4Gmd" x1="22.918" x2="22.549" y1="5.345" y2="6.133" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="iGgZmQl" x1="13.264" x2="15.031" y1="19.026" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="i7ccoc8qs"/><stop offset="1" class="waah2bcle"/></linearGradient><linearGradient id="iuPT4Kc" x1="19.343" x2="17.937" y1="18.573" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="hnwux9dcc"/><stop offset="1" class="xsno6rw2t"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="icEqrcb" x1="15.288" x2="12.882" y1="25.263" y2="25.294" gradientUnits="userSpaceOnUse"><stop offset=".113" class="yf70htb_x"/><stop offset="1" class="j2t0-ibcg"/></linearGradient><linearGradient id="i6NcB5w" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="jfv9nbbub"/><stop offset="1" class="syp0_bc6o"/></linearGradient><linearGradient id="iR15onA" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="iDWZ8ed" x1="18.825" x2="18.351" y1="24.378" y2="24.091" gradientUnits="userSpaceOnUse"><stop class="j834f-b0x"/><stop offset="1" class="t0ieoim-m"/></linearGradient><linearGradient id="iFc3g8a" x1="15.749" x2="17.116" y1="25.981" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="iFc0eqy" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="rlgwf126s"/><stop offset="1" class="l-4shobes"/></linearGradient><linearGradient id="iZeEFzX" x1="13.267" x2="15.457" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop offset=".01" class="jv6lqw6zm"/><stop offset="1" class="r3o1jnbex"/></linearGradient><linearGradient id="iaW1cmd" x1="18.593" x2="16.593" y1="15.23" y2="15.23" gradientUnits="userSpaceOnUse"><stop class="xxjj5obiq"/><stop offset="1" class="teavi7b3d"/></linearGradient><linearGradient id="iqcIBfc" x1="18.906" x2="18.453" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="ma_coc6av"/><stop offset="1" class="g9j7gtogb"/></linearGradient><linearGradient id="iT64Wjd" x1="22.63" x2="20.036" y1="11.605" y2="13.448" gradientUnits="userSpaceOnUse"><stop offset=".453" class="pcb1i7bpl"/><stop offset="1" class="c84uw1bwv"/></linearGradient><linearGradient id="is2IIbG" x1="22.059" x2="21.755" y1="8.558" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="pcb1i7bpl"/><stop offset="1" class="c84uw1bwv"/></linearGradient><linearGradient id="ipVew1d" x1="23.372" x2="22.865" y1="9.113" y2="9.957" gradientUnits="userSpaceOnUse"><stop class="pcb1i7bpl"/><stop offset="1" class="c84uw1bwv"/></linearGradient><linearGradient id="i4P74Ce" x1="13.941" x2="13.664" y1="8.052" y2="8.052" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iK1xdoe" x1="18.539" x2="18.184" y1="7.458" y2="8.558" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="imbyLKc" x1="17.751" x2="14.439" y1="8.1" y2="8.594" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iP2r41d" x1="13.66" x2="14.643" y1="9.269" y2="9.208" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iRqmCUc" x1="16.417" x2="20.154" y1="6.635" y2="5.349" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iaS389d" x1="15.626" x2="16.033" y1="8.386" y2="8.386" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="itjKSgb" x1="16.408" x2="15.963" y1="8.526" y2="8.52" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iALGF6c" x1="16.085" x2="16.085" y1="8.848" y2="8.599" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="io5fovd" x1="15.551" x2="15.74" y1="9.548" y2="9.25" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ijBggGe" x1="17.283" x2="17.147" y1="7.659" y2="7.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9Rc3fd" x1="15.376" x2="15.24" y1="7.659" y2="7.743" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPUPF1d" x1="17.29" x2="17.108" y1="6.731" y2="6.358" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ib8vdcb" x1="14.989" x2="14.473" y1="6.675" y2="6.459" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iUBMbed" x1="13.979" x2="13.979" y1="5.801" y2="6.737" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-fairy-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.agbclbc9u {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.881 7.878l-.355.737c-.044.152.061.304.211.304h.32c.15 0 .256-.154.212-.304l-.216-.737c-.047-.163-.123-.163-.172 0");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ajsjeuojy {
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.ar7i_ib9g {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
  fill: var(--svg-color--371d2d, #371D2D);
}

.asecgoboj {
  stop-color: var(--svg-color--422c2d, #422C2D);
  stop-opacity: 0;
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bm7tflbxn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.721 6.689c.187-.033.55-.024.802.172");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bvr_w2nyb {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.037 7.31c.283 0 .522.196.587.46a.12.12 0 0 1-.116.147h-.967a.1.1 0 0 1-.099-.117a.606.606 0 0 1 .595-.49");
}

.c84uw1bwv {
  stop-color: var(--svg-color--5a4544, #5A4544);
  stop-opacity: 0;
}

.c9v8_hpvm {
  stop-color: var(--svg-color--3f76a9, #3F76A9);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dixb6cljt {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.129c.1.103.144.418-.094.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.dpqo2gbuc {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.963 7.31a.606.606 0 0 0-.587.46a.12.12 0 0 0 .116.147h.967a.1.1 0 0 0 .099-.117a.61.61 0 0 0-.595-.49");
}

.dqp3b0bfm {
  stop-color: var(--svg-color--523f3d, #523F3D);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dujjp1bsn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.035 5.844v.39c-.004.064-.03.208-.112.27");
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

.e5m3cbc6k {
  stop-color: var(--svg-color--422c2d, #422C2D);
}

.e96vxibaa {
  cx: 14.936px;
  cy: 7.594px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.ev6-__b2a {
  stop-color: var(--svg-color--5c4a49, #5C4A49);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fq5b1gb4r {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.835 7.807l-.23.738a.234.234 0 0 0 .225.303h.341c.16 0 .273-.154.226-.303l-.23-.738c-.05-.163-.28-.163-.332 0");
}

.ft5dv1b6b {
  fill: none;
}

.fwk98bb0c {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.439 7.053a.47.47 0 0 1-.215.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
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

.h5h3n5mvw {
  cx: 18.068px;
  cy: 7.931px;
  r: 0.432px;
  fill: var(--svg-color--463133, #463133);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hd2qg8bsb {
  d: path("M16.947 7.428a.387.387 0 0 1 .373.49h-.748a.388.388 0 0 1 .375-.489");
}

.hnwux9dcc {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.i7ccoc8qs {
  stop-color: var(--svg-color--3968ab, #3968AB);
}

.i8qnejbvt {
  d: path("M17.292 7.764a.36.36 0 0 0-.1-.2l-.114.124l.051.098z");
}

.ikgkim2qs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 8.558v.505a1 1 0 0 0 .433.824l.215.147");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.is1z44opp {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16 9.289c-.22 0-.426-.052-.6-.143c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.368a.82.82 0 0 0 .686-.367c.038-.056-.026-.121-.085-.09c-.174.09-.379.142-.601.142");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j2t0-ibcg {
  stop-color: var(--svg-color--493032, #493032);
}

.j5n991bkm {
  fill: var(--svg-color--000, #000);
  d: path("M16.725 7.816a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j807r45wk {
  stop-color: var(--svg-color--3f2628, #3F2628);
  stop-opacity: 0;
}

.j834f-b0x {
  stop-color: var(--svg-color--584249, #584249);
}

.jfv9nbbub {
  stop-color: var(--svg-color--473534, #473534);
}

.jtrouob-f {
  fill: var(--svg-color--452c2c, #452C2C);
  d: path("m21.499 12.27l-3.145-1.206l-.136 2.175l3.578 1.368c.185.083.651.2 1.039 0s.515-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.038.494.276.836.437.961z");
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

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kcor2lvvo {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
}

.kpd4qxbil {
  cx: 13.941px;
  cy: 7.931px;
  r: 0.724px;
}

.krisv8b8a {
  cx: 14.936px;
  cy: 7.594px;
  rx: 0.169px;
  ry: 0.086px;
}

.ksyyunbhv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.919 7.51c.027.037-.03.082-.096.131c-.066.05-.114.084-.142.047s.003-.107.069-.156c.065-.049.14-.059.169-.022");
}

.l-4shobes {
  stop-color: var(--svg-color--358dea, #358DEA);
}

.l5nncxbgw {
  cx: 18.068px;
  cy: 7.931px;
  r: 0.724px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lh4nfkb5q {
  stop-color: var(--svg-color--382223, #382223);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.ly32g8bmi {
  fill: var(--svg-color--422c2d, #422C2D);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m0dkjhbrx {
  width: 0.703px;
  height: 4.633px;
  x: 22.34px;
  y: 4.997px;
  rx: 0.352px;
}

.m3w1habwo {
  d: path("M16.919 7.51c.027.037-.03.082-.096.131c-.066.05-.114.084-.142.047s.003-.107.069-.156c.065-.049.14-.059.169-.022");
}

.ma_coc6av {
  stop-color: var(--svg-color--51a3e8, #51A3E8);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.muxg66bas {
  width: 0.703px;
  height: 4.633px;
  x: 22.34px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.mz44h-bzv {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m18.091 5.121l.186.093a.85.85 0 0 1 .442.925l-.256 1.319c-.023.136-.113.228-.248.231h-.008s.024-.393.047-.624c.019-.188-.014-.245-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.861-.185-1.699-.185c-.837 0-1.419.115-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.07-.14.208-.14.324c.024.254.047.624.047.624h-.021a.275.275 0 0 1-.258-.231l-.256-1.319a.89.89 0 0 1 .465-.902l.187-.093c.116-.069.232-.161.348-.254l.42-.44a.85.85 0 0 1 .953-.138c.233.07.489.07.721 0a1.05 1.05 0 0 1 1.024.231l.35.347a.95.95 0 0 0 .348.254");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n-gofxbqk {
  fill: var(--svg-color--3c8aea, #3C8AEA);
  d: path("M13.264 21.733V16.26l5.528.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n6_mbsb0e {
  d: path("m15.835 7.807l-.23.738a.234.234 0 0 0 .225.303h.341c.16 0 .273-.154.226-.303l-.23-.738c-.05-.163-.28-.163-.332 0");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nkm4r8_8f {
  stop-color: var(--svg-color--4780ac, #4780AC);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nr39ys81r {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M14.364 6.752V6.75h.002l.002-.002l.005-.004l.067-.047a1.23 1.23 0 0 1 .83-.16a.232.232 0 0 1-.073.457a.77.77 0 0 0-.511.095l-.024.016l-.003.003a.232.232 0 0 1-.295-.357");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.nzqb2mw4u {
  d: path("M15.406 7.77c0-.125-.101-.208-.129-.234l-.125.121l.077.157z");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o9iemhbma {
  stop-color: var(--svg-color--4a2f2f, #4A2F2F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oisgcibyz {
  fill: var(--svg-color--51383b, #51383B);
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.oreqjlb-y {
  d: path("M15.053 7.428a.387.387 0 0 0-.373.49h.747a.39.39 0 0 0-.375-.49");
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.pb1pwib-r {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .005-4.88a3.454 3.454 0 0 1 4.881-.006l1.19 1.19c.337.337.601.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.pcb1i7bpl {
  stop-color: var(--svg-color--5a4544, #5A4544);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.ptfvfcbrt {
  stop-color: var(--svg-color--435e8c, #435E8C);
}

.q26bd-bbw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.457 6.914c.142-.126.452-.258.836-.197");
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qlvkqabeg {
  stop-color: var(--svg-color--331e1e, #331E1E);
}

.qpfi3-_om {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16 9.289c-.22 0-.426-.052-.6-.143c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.368a.82.82 0 0 0 .686-.367c.038-.056-.026-.121-.085-.09c-.174.09-.379.142-.601.142Z");
}

.qqobt5tvr {
  d: path("M13.264 21.733V16.26l5.528.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
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

.rsfgarwma {
  stop-color: var(--svg-color--5c4a49, #5C4A49);
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

.s545islfz {
  d: path("m17.72 5.492l-1.335.445a.454.454 0 0 0 .204.88l1.327-.177z");
}

.s7kqzl5sm {
  d: path("m13.789 7.665l.021.001s-.023-.37-.046-.624c0-.116.046-.255.14-.324l.069-.07a.46.46 0 0 0 .163-.37v-.37c0-.116.07-.208.186-.231c.28-.07.86-.185 1.698-.185s1.42.115 1.699.185a.25.25 0 0 1 .186.231v.37c0 .139.07.278.163.37c.217.153.204.237.186.417c-.023.231-.047.624-.047.624h.008L18.1 9.406c-.07.768-.673 1.303-1.393 1.303h-1.392c-.743 0-1.323-.535-1.393-1.303z");
}

.saunobcmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 12.667l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.syp0_bc6o {
  stop-color: var(--svg-color--473534, #473534);
  stop-opacity: 0;
}

.t0dfidbsh {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
  stop-opacity: 0;
}

.t0ieoim-m {
  stop-color: var(--svg-color--584249, #584249);
  stop-opacity: 0;
}

.t16p7zajb {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.863-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.teavi7b3d {
  stop-color: var(--svg-color--3b9bf4, #3B9BF4);
  stop-opacity: 0;
}

.tn00ksbky {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.235-3.836z");
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

.u66aotmpr {
  stop-color: var(--svg-color--523f3d, #523F3D);
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
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

.uqdhtogep {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M17.614 6.751h-.001l-.002-.002l-.005-.004l-.068-.047a1.23 1.23 0 0 0-.83-.16a.232.232 0 0 0 .073.457a.77.77 0 0 1 .512.095l.027.019a.231.231 0 0 0 .294-.358");
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uvyxh01-z {
  stop-color: var(--svg-color--2851b6, #2851B6);
}

.uz8dj8b7c {
  stop-color: var(--svg-color--5f4a49, #5F4A49);
}

.uz8kaou5q {
  stop-color: var(--svg-color--392c45, #392C45);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vms7zebge {
  fill: var(--svg-color--47302d, #47302D);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.129c.1.103.144.418-.094.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
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

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w2mg53b0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .284.31L20.5 11.24l.84.086a.21.21 0 0 1-.043.418l-1.21-.124l-.955.875a.21.21 0 1 1-.284-.31z");
}

.waah2bcle {
  stop-color: var(--svg-color--3968ab, #3968AB);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wj6ixej_e {
  fill: var(--svg-color--000, #000);
  d: path("M15.274 7.815a.22.22 0 0 0-.221-.221a.22.22 0 0 0-.197.323h.392a.2.2 0 0 0 .026-.102");
}

.wke8dtqov {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .216-.373l.054-.894z");
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xfs4fx4gd {
  d: path("m18.091 5.121l.186.093a.85.85 0 0 1 .442.925l-.256 1.319c-.023.136-.113.228-.248.231h-.008s.024-.393.047-.624c.019-.188-.014-.245-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.861-.185-1.699-.185c-.837 0-1.419.115-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.07-.14.208-.14.324c.024.254.047.624.047.624h-.021a.275.275 0 0 1-.258-.231l-.256-1.319a.89.89 0 0 1 .465-.902l.187-.093c.116-.069.232-.161.348-.254l.42-.44a.85.85 0 0 1 .953-.138c.233.07.489.07.721 0a1.05 1.05 0 0 1 1.024.231l.35.347a.95.95 0 0 0 .348.254");
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xsno6rw2t {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
  stop-opacity: 0;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xxjj5obiq {
  stop-color: var(--svg-color--4db6ff, #4DB6FF);
}

.y39x50mqx {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
}

.yatrv-bpo {
  cx: 13.941px;
  cy: 7.931px;
  r: 0.432px;
}

.yf70htb_x {
  stop-color: var(--svg-color--5a4343, #5A4343);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yn_cprukr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.025-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .283-.312l-4.235-3.836z");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.ywk-_ln5y {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
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

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z5e-1sbyl {
  stop-color: var(--svg-color--5f4a49, #5F4A49);
  stop-opacity: 0;
}

.z750v9bmx {
  cx: 18.068px;
  cy: 7.931px;
  r: 0.432px;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.zh46g387g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 8.935v.258a.9.9 0 0 1-.25.617v0");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx20zqh8j {
  stop-color: var(--svg-color--3f2628, #3F2628);
}

.zz3980hzg {
  stop-color: var(--svg-color--382223, #382223);
}

</style>
