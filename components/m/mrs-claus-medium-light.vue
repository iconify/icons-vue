<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="exzcvx4en"/><path fill="url(#i2EK6Ab)" class="pidu3gbxk"/><path fill="url(#iKyRS6c)" class="pidu3gbxk"/><g filter="url(#i6Z271b)"><path fill="url(#i0rKaMv)" class="ilcc3dbfe"/></g><g filter="url(#in1LMoe)"><path fill="url(#iIU54Zb)" class="m6yqys39r"/></g><path fill="url(#i8FVf0i)" class="q612z752i"/><path fill="url(#ixjZ8Qd)" class="q612z752i"/><path fill="url(#iR8r4ib)" class="q612z752i"/><path fill="url(#i5yjZSc)" class="q612z752i"/><path fill="url(#iQrynLe)" class="q612z752i"/><path fill="url(#i95b8vd)" class="q612z752i"/><path fill="url(#iuWPNvb)" class="q612z752i"/><path fill="url(#ieDfYbn)" class="q612z752i"/><path fill="url(#ilQvNQd)" class="q612z752i"/><path fill="url(#ip8WnXd)" class="q612z752i"/><path fill="url(#iX5B9fc)" class="q612z752i"/><g filter="url(#i1J9MUc)"><path fill="url(#iXZI2Bd)" class="r6b7ix18y"/></g><g filter="url(#iv8vrke)"><path fill="url(#iJZwRle)" class="tbow2ebjl"/></g><g filter="url(#iZEYqJc)"><path class="fqeyu7zlc"/></g><g filter="url(#iZp2sKd)"><path class="n292jgsxz"/><path fill="url(#ixaQ8fc)" class="h6hhn-36x"/><path fill="url(#idFZnQd)" class="h6hhn-36x"/><path fill="url(#iUPlmMd)" class="h6hhn-36x"/><path fill="url(#iUu4Ebc)" class="h6hhn-36x"/><path fill="url(#iSvDGNc)" class="h6hhn-36x"/><path fill="url(#iXMGVUc)" class="h6hhn-36x"/></g><g filter="url(#ie2TRJe)"><path stroke="url(#iGsdYoc)" class="m0j3jgbjt"/></g><path class="wpzk5jw3v"/><g filter="url(#invKXye)"><path class="za1tbsb_m"/></g><g filter="url(#ia4esDc)"><path class="zdciykbsu"/></g><path class="pclqe2vzi"/><path fill="url(#ikujzDe)" class="uxt4me83a"/><path class="d-aoac-ft"/><g filter="url(#i01SvbL)"><path class="pk4qrvtef"/><path fill="url(#iI9U1bt)" class="ie__x2bvj"/></g><g filter="url(#iwGwrgD)"><path fill="url(#iWZ0TCO)" class="ny7-5tbal"/></g><path class="wskvwr48a"/><path fill="url(#idrbyJb)" class="ijoxtwddc"/><path class="m0wg8vbqd"/><g filter="url(#izx2dYd)"><path fill="url(#ikk1Old)" class="mceyoyhkc"/></g><g filter="url(#ikFQBDe)"><ellipse transform="rotate(-27.914 11.437 17.554)" class="c4uvfdcmx"/><ellipse fill="url(#iExDshc)" transform="rotate(-27.914 11.437 17.554)" class="j2hk8r5lm"/></g><g filter="url(#i3w3tod)"><path fill="url(#i2Au2Id)" class="kopam7esf"/><path fill="url(#iuQGo1b)" class="kopam7esf"/><path fill="url(#iEVpfPb)" class="kopam7esf"/><path fill="url(#ii2GhIe)" class="kopam7esf"/></g><g filter="url(#iNeGzCd)"><path clip-rule="evenodd" class="avhdydbkl"/></g><g filter="url(#iBHHGyb)"><path clip-rule="evenodd" class="zf-dr2bxb"/></g><g filter="url(#ikCnpac)"><path clip-rule="evenodd" class="q-py-xa8l"/><path fill="url(#i78BFNe)" clip-rule="evenodd" class="qo6lmkbuu"/><path fill="url(#iHaDXSd)" clip-rule="evenodd" class="qo6lmkbuu"/><path fill="url(#iKkEMec)" clip-rule="evenodd" class="qo6lmkbuu"/></g><g filter="url(#iZCa0ns)"><path clip-rule="evenodd" class="pyimo2blq"/><path fill="url(#iPZNmed)" clip-rule="evenodd" class="c8qm4b0_a"/><path fill="url(#iUNVdDd)" clip-rule="evenodd" class="c8qm4b0_a"/></g><g filter="url(#iXqdBNe)"><path class="lmc_3jx7c"/><path fill="url(#idY5DSb)" class="zcaxasb6b"/><path fill="url(#i8vDByD)" class="zcaxasb6b"/></g><path fill="url(#iw4eyQK)" class="zcaxasb6b"/><g filter="url(#i1r7MGc)"><path class="vfyzwablh"/><path fill="url(#iNy0TIe)" class="lytc0obul"/><path fill="url(#iGkz69d)" class="lytc0obul"/></g><g filter="url(#i9McBZb)"><path class="r165x48_t"/><path fill="url(#innVyIb)" class="p3ialubfs"/></g><g filter="url(#iyAHoef)"><path stroke="url(#ivMG4rO)" class="senludb5g"/></g><g filter="url(#iaSTixb)"><path stroke="url(#ixvsBue)" class="gby3b7dbp"/></g><g filter="url(#iBSwgDc)"><path fill="url(#iEqhXse)" class="mzc8gl1kv"/><path fill="url(#i9bvngb)" class="mzc8gl1kv"/></g><g filter="url(#iym8xUd)"><path fill="url(#iwJJnwd)" class="b-agi75gn"/></g><g filter="url(#iVruEmb)"><path fill="url(#i0sWsne)" class="l235i7b0i"/><path fill="url(#i3k4yHE)" class="l235i7b0i"/><path fill="url(#ifSuHYb)" class="l235i7b0i"/></g><g filter="url(#i4yMtPw)"><path fill="url(#inOpZse)" class="s5l3r5b8v"/></g><g filter="url(#iJh4ajd)"><path fill="url(#i9ud44d)" class="awl12cr_n"/><path fill="url(#iuBcITc)" class="awl12cr_n"/><path fill="url(#ieoQAsW)" class="awl12cr_n"/></g><g filter="url(#iG76nFb)"><path fill="url(#iJ6jWBe)" class="lyk395t8a"/><path fill="url(#iAkuluE)" class="lyk395t8a"/></g><defs><radialGradient id="i2EK6Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-15.1875 0 0 -10.125 21.381 6.31)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="mzycncwxb"/><stop offset="1" class="o6ackn6vy"/></radialGradient><radialGradient id="iKyRS6c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 4.6875 -5.60964 -8.00307 25.475 4.248)" gradientUnits="userSpaceOnUse"><stop class="vn83tqcbo"/><stop offset="1" class="c47ug_iov"/></radialGradient><radialGradient id="i0rKaMv" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.023 17.622)scale(4.54255 3.9894)" gradientUnits="userSpaceOnUse"><stop class="fp3hkv_bh"/><stop offset=".905" class="jplxqgtye"/></radialGradient><radialGradient id="iIU54Zb" cx="0" cy="0" r="1" gradientTransform="rotate(49.526 -18.248 14.506)scale(3.89961)" gradientUnits="userSpaceOnUse"><stop class="ck2myom8o"/><stop offset="1" class="t6giq_bqy"/></radialGradient><radialGradient id="i8FVf0i" cx="0" cy="0" r="1" gradientTransform="rotate(149.208 8.4 11.067)scale(14.0258 18.6055)" gradientUnits="userSpaceOnUse"><stop class="g3qionb9g"/><stop offset=".693" class="gt-5izbkr"/></radialGradient><radialGradient id="ixjZ8Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.74998 4.56596 -7.7871 -11.5119 27.875 19.694)" gradientUnits="userSpaceOnUse"><stop class="twp3ygv2w"/><stop offset="1" class="dxm4fulvj"/></radialGradient><radialGradient id="iR8r4ib" cx="0" cy="0" r="1" gradientTransform="rotate(127.567 2.283 7.86)scale(7.23949 5.43951)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="spesxfync"/><stop offset="1" class="nt1lt3_he"/></radialGradient><radialGradient id="i5yjZSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.94504 -6.31736 21.40368 6.58995 13.743 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="rwumr017n"/><stop offset="1" class="qt6wr2b4a"/></radialGradient><radialGradient id="iQrynLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.5929 -12.9934 0 15.93 17.52)" gradientUnits="userSpaceOnUse"><stop offset=".937" class="ldsslmbvc"/><stop offset="1" class="p_0c2tyib"/></radialGradient><radialGradient id="iuWPNvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0839 -2.91528 2.89208 -1.07527 12.075 17.373)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="nzscevbgj"/><stop offset="1" class="i90fnrxjj"/></radialGradient><radialGradient id="ieDfYbn" cx="0" cy="0" r="1" gradientTransform="rotate(88.793 4.148 20.936)scale(6.22593 .25853)" gradientUnits="userSpaceOnUse"><stop offset=".571" class="nn382jjct"/><stop offset="1" class="xuds1wbpf"/></radialGradient><radialGradient id="ilQvNQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -2.90625 2.90512 1.28075 20.492 17.613)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="ahwun0t2j"/><stop offset="1" class="e-oulg67i"/></radialGradient><radialGradient id="ip8WnXd" cx="0" cy="0" r="1" gradientTransform="rotate(91.393 -3.97 10.391)scale(8.0453 1.59313)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="ukdu4-bnh"/><stop offset="1" class="i7__0tbbl"/></radialGradient><radialGradient id="iX5B9fc" cx="0" cy="0" r="1" gradientTransform="matrix(5.52367 3.3946 -1.1446 1.86247 21.813 11.906)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="lba0g0b-f"/><stop offset="1" class="suyfdv57p"/></radialGradient><radialGradient id="iXZI2Bd" cx="0" cy="0" r="1" gradientTransform="matrix(5.1875 1.28125 -1.21262 4.90965 17.788 21.092)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="md1neftgk"/><stop offset="1" class="fdkmwfizl"/></radialGradient><radialGradient id="iJZwRle" cx="0" cy="0" r="1" gradientTransform="rotate(101.083 -2.836 15.043)scale(3.08885 4.56981)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="z3bpdx_xu"/><stop offset="1" class="s4m35hbub"/></radialGradient><radialGradient id="idFZnQd" cx="0" cy="0" r="1" gradientTransform="matrix(.33253 -1.58667 8.92883 1.87128 15.615 22.452)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="k-_0f494i"/><stop offset="1" class="ymq-6qbvn"/></radialGradient><radialGradient id="iUPlmMd" cx="0" cy="0" r="1" gradientTransform="matrix(.96093 1.53907 -.79747 .4979 17.52 19.992)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="a2w8_7abr"/><stop offset="1" class="cvk5tcb7t"/></radialGradient><radialGradient id="iUu4Ebc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 0 0 -.4735 16.888 21.28)" gradientUnits="userSpaceOnUse"><stop class="z2ncl2bsp"/><stop offset="1" class="wokvbnbir"/></radialGradient><radialGradient id="iXMGVUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.67187 2.09192 0 15.947 20.843)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="msq_ndbcs"/><stop offset="1" class="es2lqabwv"/></radialGradient><radialGradient id="ikujzDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23439 1.98436 -2.08903 -1.2995 20.789 17.265)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="kz8v_2b0u"/><stop offset="1" class="t_fhyk9zs"/></radialGradient><radialGradient id="iI9U1bt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.15 4.157)scale(.69518 .9571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idrbyJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23439 1.98437 -2.08904 -1.2995 12.763 17.265)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="kz8v_2b0u"/><stop offset="1" class="t_fhyk9zs"/></radialGradient><radialGradient id="iExDshc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01423 -.90865 1.09224 -.0171 11.41 18.132)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuQGo1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.1076 1.90987 -2.1901 -.12338 10.615 4.865)" gradientUnits="userSpaceOnUse"><stop class="o-gllcbpi"/><stop offset="1" class="op8gn6bnt"/></radialGradient><radialGradient id="iEVpfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23266 0 0 -5.95693 7.091 18.799)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="c3098ubep"/><stop offset=".808" class="ixxpbv8hf"/></radialGradient><radialGradient id="ii2GhIe" cx="0" cy="0" r="1" gradientTransform="rotate(118.957 8.495 15.24)scale(5.35726 1.55455)" gradientUnits="userSpaceOnUse"><stop class="paruexevs"/><stop offset="1" class="lcus7p0ww"/></radialGradient><radialGradient id="i78BFNe" cx="0" cy="0" r="1" gradientTransform="rotate(131.743 -.215 11.567)scale(.68059 .35127)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="egvfrgbew"/><stop offset="1" class="i6zk_phor"/></radialGradient><radialGradient id="iKkEMec" cx="0" cy="0" r="1" gradientTransform="matrix(.5337 0 0 .67969 6.495 19.347)" gradientUnits="userSpaceOnUse"><stop class="du3zqdbas"/><stop offset="1" class="eo5th8odz"/></radialGradient><radialGradient id="iPZNmed" cx="0" cy="0" r="1" gradientTransform="matrix(-.49463 .28469 -.39079 -.67897 25.557 18.944)" gradientUnits="userSpaceOnUse"><stop class="yace-6bkn"/><stop offset="1" class="x6b7fvhjk"/></radialGradient><radialGradient id="idY5DSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80005 -1.45312 .28898 -.1591 17.68 18.999)" gradientUnits="userSpaceOnUse"><stop class="pi9myibky"/><stop offset="1" class="a4r8facys"/></radialGradient><radialGradient id="i8vDByD" cx="0" cy="0" r="1" gradientTransform="matrix(.57813 -1.10938 .29816 .15538 14.678 19.155)" gradientUnits="userSpaceOnUse"><stop class="x6t_0e-6t"/><stop offset="1" class="n01394_5x"/></radialGradient><radialGradient id="iw4eyQK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96021 -1.0123 1.0168 -1.96892 16.225 19.545)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="tygkjs-ny"/><stop offset=".937" class="lqfy3p-zi"/></radialGradient><radialGradient id="iEqhXse" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63619 -5.40116 1.4488 -.70713 8.006 12.827)" gradientUnits="userSpaceOnUse"><stop class="cvqywpbya"/><stop offset="1" class="do75vybld"/></radialGradient><radialGradient id="i9bvngb" cx="0" cy="0" r="1" gradientTransform="matrix(.55304 6.50969 -3.32228 .28225 6.553 8.28)" gradientUnits="userSpaceOnUse"><stop offset=".505" class="tjn-pbcga"/><stop offset="1" class="q270rhb2n"/></radialGradient><radialGradient id="iwJJnwd" cx="0" cy="0" r="1" gradientTransform="matrix(5.54388 1.16889 -2.00192 9.49486 22.68 11.454)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="o0zfjub8g"/><stop offset=".932" class="emarm55as"/></radialGradient><radialGradient id="i0sWsne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93356 -6.50176 2.0863 -.62045 10.645 11.694)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="hffkdxxqc"/><stop offset="1" class="pew6frnzi"/></radialGradient><radialGradient id="i3k4yHE" cx="0" cy="0" r="1" gradientTransform="rotate(162.165 4.707 5.45)scale(3.24962 5.81408)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="d2xfa78kb"/><stop offset="1" class="bemgdwb7k"/></radialGradient><radialGradient id="ifSuHYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.39841 -3.90671 0 9.63 8.147)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="h13c6fb3k"/><stop offset="1" class="k-7dzim-i"/></radialGradient><radialGradient id="inOpZse" cx="0" cy="0" r="1" gradientTransform="rotate(32.247 -3.934 40.273)scale(5.50541 6.13649)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="q63b76bcm"/><stop offset="1" class="l_nupdb1h"/></radialGradient><radialGradient id="i9ud44d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.34375 4.69757 0 15.819 8.592)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ea88qbbkv"/><stop offset="1" class="l_hht1tza"/></radialGradient><radialGradient id="ieoQAsW" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03127 5.6875 -4.70513 -1.68042 13.663 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".544" class="o8-p00v9r"/><stop offset="1" class="kpi-j7bnf"/></radialGradient><radialGradient id="iJ6jWBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.78125 3.21875 0 19.847 8.905)" gradientUnits="userSpaceOnUse"><stop class="gh7w8ccdd"/><stop offset="1" class="q90nxab-j"/></radialGradient><radialGradient id="iAkuluE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 2.25 -3.86674 -5.58532 19.756 7.405)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="ju711jbwd"/><stop offset="1" class="ep--azv6o"/></radialGradient><filter id="i6Z271b" width="6.033" height="6.033" x="22.017" y="15.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="in1LMoe" width="6.033" height="5.933" x="3.945" y="16.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="i1J9MUc" width="8.322" height="4.297" x="15.869" y="19.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".375"/></filter><filter id="iv8vrke" width="8.322" height="4.297" x="6.962" y="19.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".375"/></filter><filter id="iZEYqJc" width="4.312" height="5.936" x="13.421" y="17.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".25"/></filter><filter id="iZp2sKd" width="3.555" height="4.778" x="14.22" y="17.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.533333 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="ie2TRJe" width="6.478" height="2.472" x="12.708" y="23.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".05"/></filter><filter id="invKXye" width="5.356" height="2.366" x="18.049" y="16.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0588235 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="ia4esDc" width="5.356" height="2.366" x="8.696" y="16.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0588235 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="i01SvbL" width="1.278" height="1.112" x="18.696" y="17.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".05"/></filter><filter id="iwGwrgD" width="1.303" height="1.343" x="20.326" y="17.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".1"/></filter><filter id="izx2dYd" width="1.477" height="1.576" x="12.155" y="17.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".1"/></filter><filter id="ikFQBDe" width="1.511" height="1.128" x="10.681" y="16.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".05"/></filter><filter id="i3w3tod" width="25.121" height="17.787" x="3.515" y="3.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.615686 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="iNeGzCd" width="4.251" height="1.951" x="8.893" y="13.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.415686 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.32549 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24207" result="effect2_innerShadow_3987_24207"/></filter><filter id="iBHHGyb" width="4.251" height="1.951" x="18.821" y="13.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.415686 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.32549 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24207" result="effect2_innerShadow_3987_24207"/></filter><filter id="ikCnpac" width="2.77" height=".9" x="6.495" y="18.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.392157 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="iZCa0ns" width="2.97" height=".9" x="22.788" y="18.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.435294 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="iXqdBNe" width="3.466" height="1.925" x="14.265" y="17.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.447059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/></filter><filter id="i1r7MGc" width="6.862" height="2.837" x="16.957" y="18.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24207" result="effect2_innerShadow_3987_24207"/></filter><filter id="i9McBZb" width="6.862" height="2.837" x="8.05" y="18.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24207"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24207" result="effect2_innerShadow_3987_24207"/></filter><filter id="iyAHoef" width="3.891" height="1.346" x="9.038" y="13.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".125"/></filter><filter id="iaSTixb" width="3.891" height="1.346" x="19.032" y="13.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".125"/></filter><filter id="iBSwgDc" width="6.389" height="9.227" x="3.959" y="6.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".25"/></filter><filter id="iym8xUd" width="6.538" height="8.968" x="21.546" y="6.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".25"/></filter><filter id="iVruEmb" width="5.609" height="9.353" x="6.825" y="4.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".25"/></filter><filter id="i4yMtPw" width="5.609" height="9.353" x="19.837" y="4.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".25"/></filter><filter id="iJh4ajd" width="6.2" height="9.592" x="9.977" y="3.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".3"/></filter><filter id="iG76nFb" width="6.2" height="9.592" x="15.705" y="3.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24207" stdDeviation=".3"/></filter><linearGradient id="i95b8vd" x1="6.563" x2="9.75" y1="19.694" y2="19.978" gradientUnits="userSpaceOnUse"><stop offset=".21" class="b0b9hclau"/><stop offset="1" class="vmhj67bpb"/></linearGradient><linearGradient id="ixaQ8fc" x1="17.675" x2="15.947" y1="21" y2="21.093" gradientUnits="userSpaceOnUse"><stop offset=".282" class="nk5qlqb2c"/><stop offset="1" class="gwc2yyjnf"/></linearGradient><linearGradient id="iSvDGNc" x1="14.35" x2="15.144" y1="20.063" y2="20.35" gradientUnits="userSpaceOnUse"><stop class="jxixhlcpv"/><stop offset="1" class="nb1ng5muw"/></linearGradient><linearGradient id="iGsdYoc" x1="14.605" x2="15.438" y1="25.495" y2="23.891" gradientUnits="userSpaceOnUse"><stop class="ubudbcc-l"/><stop offset="1" class="m1djvtbjd"/></linearGradient><linearGradient id="iWZ0TCO" x1="21.394" x2="20.817" y1="17.829" y2="18.184" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikk1Old" x1="13.305" x2="12.728" y1="17.829" y2="18.184" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2Au2Id" x1="26.288" x2="10.475" y1="14.686" y2="14.686" gradientUnits="userSpaceOnUse"><stop class="o1xctu8tq"/><stop offset="1" class="e3tydgbfn"/></linearGradient><linearGradient id="iHaDXSd" x1="7.879" x2="7.879" y1="18.916" y2="19.139" gradientUnits="userSpaceOnUse"><stop class="unozt67tp"/><stop offset="1" class="sjitiy62y"/></linearGradient><linearGradient id="iUNVdDd" x1="24.172" x2="24.172" y1="18.944" y2="19.143" gradientUnits="userSpaceOnUse"><stop class="t233yurnp"/><stop offset="1" class="dte4ogbdr"/></linearGradient><linearGradient id="iNy0TIe" x1="21.35" x2="21.35" y1="21.725" y2="20.326" gradientUnits="userSpaceOnUse"><stop offset=".006" class="xcvhc4axz"/><stop offset="1" class="fl8h_cbee"/></linearGradient><linearGradient id="iGkz69d" x1="18.795" x2="20.686" y1="19.936" y2="20.67" gradientUnits="userSpaceOnUse"><stop class="xh84v07wd"/><stop offset=".141" class="akeuncc3p"/><stop offset=".868" class="akeuncc3p"/><stop offset="1" class="xh84v07wd"/></linearGradient><linearGradient id="innVyIb" x1="12.655" x2="10.655" y1="20.662" y2="19.819" gradientUnits="userSpaceOnUse"><stop class="p9zg-objl"/><stop offset=".141" class="yg9ra3bzd"/><stop offset=".868" class="yg9ra3bzd"/><stop offset="1" class="p9zg-objl"/></linearGradient><linearGradient id="ivMG4rO" x1="12.553" x2="9.154" y1="14.215" y2="15.118" gradientUnits="userSpaceOnUse"><stop offset=".166" class="g8eaedcck"/><stop offset="1" class="jnjw33b1s"/></linearGradient><linearGradient id="ixvsBue" x1="22.548" x2="18.399" y1="14.735" y2="14.437" gradientUnits="userSpaceOnUse"><stop offset=".166" class="g8eaedcck"/><stop offset="1" class="jnjw33b1s"/></linearGradient><linearGradient id="iuBcITc" x1="10.288" x2="13.073" y1="8.31" y2="8.31" gradientUnits="userSpaceOnUse"><stop class="h243fe46z"/><stop offset="1" class="w-amzpbim"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mrs-claus-medium-light" /></template>
<style>
.a2w8_7abr {
  stop-color: var(--svg-color--c49377, #C49377);
}

.a4r8facys {
  stop-color: var(--svg-color--d8dfe2, #D8DFE2);
  stop-opacity: 0;
}

.ahwun0t2j {
  stop-color: var(--svg-color--e3a690, #E3A690);
}

.akeuncc3p {
  stop-color: var(--svg-color--b8e1ee, #B8E1EE);
}

.avhdydbkl {
  fill: var(--svg-color--87838b, #87838B);
  fill-rule: evenodd;
  d: path("M12.555 14.834c-1.511-.274-2.56.224-2.844.457a.5.5 0 1 1-.635-.772c.526-.433 1.878-.991 3.657-.67a.5.5 0 1 1-.178.985");
}

.awl12cr_n {
  d: path("M10.577 9.123V5.201c.86-.171 1.047-.789 2.383-1.125c1.085-.195 1.593.258 2.617.641v4.625c-.663 1.647-2.365 2.619-3.47 3.028c-.308.114-.66.038-.848-.232c-.604-.867-.682-2.198-.682-3.015");
}

.b-agi75gn {
  d: path("M26.48 7.85c-.998-.559-2.004-.447-2.383-.322l-1.912 5.03c-.13.278-.436.655.673 1.018c1.1.361 1.947 1.017 2.18 1.663c.043.12.174.2.28.127c.825-.571 1.56-2.594 1.993-3.83c.471-1.345.416-2.986-.831-3.685");
}

.b0b9hclau {
  stop-color: var(--svg-color--d89e87, #D89E87);
}

.bemgdwb7k {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c47ug_iov {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
  stop-opacity: 0;
}

.c4uvfdcmx {
  cx: 11.437px;
  cy: 17.554px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.717px;
  ry: 0.363px;
}

.c8qm4b0_a {
  fill-rule: evenodd;
  d: path("M22.788 19.319c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.ck2myom8o {
  stop-color: var(--svg-color--c08671, #C08671);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvk5tcb7t {
  stop-color: var(--svg-color--c49377, #C49377);
  stop-opacity: 0;
}

.cvqywpbya {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
}

.d-aoac-ft {
  fill: var(--svg-color--000, #000);
  d: path("M19.026 18.495c0-.523.419-.94.941-.94c.523 0 .941.417.941.94a.9.9 0 0 1-.105.433h-1.665a.85.85 0 0 1-.112-.433");
}

.d2xfa78kb {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
  stop-opacity: 0;
}

.do75vybld {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
  stop-opacity: 0;
}

.dte4ogbdr {
  stop-color: var(--svg-color--c7c6ca, #C7C6CA);
  stop-opacity: 0;
}

.du3zqdbas {
  stop-color: var(--svg-color--828084, #828084);
}

.dxm4fulvj {
  stop-color: var(--svg-color--f7c39f, #F7C39F);
  stop-opacity: 0;
}

.e-oulg67i {
  stop-color: var(--svg-color--e3a690, #E3A690);
  stop-opacity: 0;
}

.e3tydgbfn {
  stop-color: var(--svg-color--bab9bc, #BAB9BC);
}

.ea88qbbkv {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
}

.egvfrgbew {
  stop-color: var(--svg-color--6f7587, #6F7587);
}

.emarm55as {
  stop-color: var(--svg-color--dbd9dd, #DBD9DD);
}

.eo5th8odz {
  stop-color: var(--svg-color--828084, #828084);
  stop-opacity: 0;
}

.ep--azv6o {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
}

.es2lqabwv {
  stop-color: var(--svg-color--d39878, #D39878);
}

.exzcvx4en {
  fill: var(--svg-color--f53742, #F53742);
  d: path("M6.038 7.498a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.125H6.038z");
}

.fdkmwfizl {
  stop-color: var(--svg-color--bd8574, #BD8574);
  stop-opacity: 0;
}

.fl8h_cbee {
  stop-color: var(--svg-color--80cce7, #80CCE7);
  stop-opacity: 0;
}

.fp3hkv_bh {
  stop-color: var(--svg-color--f7caa8, #F7CAA8);
}

.fqeyu7zlc {
  fill: var(--svg-color--be817b, #BE817B);
  d: path("m15.17 18.29l-1.206 3.13c-.19.643.268 1.286.92 1.286h1.386c.651 0 1.11-.653.92-1.287l-.939-3.129c-.2-.693-.87-.693-1.08 0");
}

.ft5dv1b6b {
  fill: none;
}

.g3qionb9g {
  stop-color: var(--svg-color--f9c39f, #F9C39F);
}

.g8eaedcck {
  stop-color: var(--svg-color--97949a, #97949A);
}

.gby3b7dbp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.548 14.735c-.354-.255-1.478-.725-3.14-.562");
}

.gh7w8ccdd {
  stop-color: var(--svg-color--f7f5f9, #F7F5F9);
}

.gt-5izbkr {
  stop-color: var(--svg-color--c08880, #C08880);
}

.gwc2yyjnf {
  stop-color: var(--svg-color--e1b6a1, #E1B6A1);
  stop-opacity: 0;
}

.h13c6fb3k {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
  stop-opacity: 0;
}

.h243fe46z {
  stop-color: var(--svg-color--b6b4b8, #B6B4B8);
}

.h6hhn-36x {
  d: path("m15.243 18.194l-.978 2.97a.993.993 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.288l-.978-2.97c-.21-.694-1.188-.694-1.408 0");
}

.hffkdxxqc {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
}

.i6zk_phor {
  stop-color: var(--svg-color--8d889f, #8D889F);
  stop-opacity: 0;
}

.i7__0tbbl {
  stop-color: var(--svg-color--ac7763, #AC7763);
  stop-opacity: 0;
}

.i90fnrxjj {
  stop-color: var(--svg-color--c3877e, #C3877E);
  stop-opacity: 0;
}

.ie__x2bvj {
  d: path("M19.844 17.2c.117.157-.127.347-.405.555c-.278.207-.484.353-.6.197c-.117-.156.013-.451.29-.659c.278-.207.598-.249.715-.093");
}

.ijoxtwddc {
  d: path("M11.934 16.852a1.643 1.643 0 0 0-1.583 2.076h3.173a1.7 1.7 0 0 0 .06-.433a1.654 1.654 0 0 0-1.65-1.643");
}

.ilcc3dbfe {
  d: path("M24.984 21.937a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j2hk8r5lm {
  cx: 11.437px;
  cy: 17.554px;
  rx: 0.717px;
  ry: 0.363px;
}

.jnjw33b1s {
  stop-color: var(--svg-color--97949a, #97949A);
  stop-opacity: 0;
}

.jplxqgtye {
  stop-color: var(--svg-color--c98e84, #C98E84);
}

.ju711jbwd {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
  stop-opacity: 0;
}

.jxixhlcpv {
  stop-color: var(--svg-color--c48f74, #C48F74);
}

.k-_0f494i {
  stop-color: var(--svg-color--c38385, #C38385);
}

.k-7dzim-i {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
}

.kopam7esf {
  d: path("M6.744 21.304a.095.095 0 0 0 .1-.09c.05-.81.162-2.752.198-3.966c.052-1.72.863-2.687 2.12-3.242a10 10 0 0 0 1.637-.795c.247-.15.44-.266.757-.385q.129-.046.32-.105c.88-.276 2.81-1.076 3.887-3.178c.085-.166.348-.157.423.014c.935 2.11 2.958 2.884 3.864 3.156q.216.063.356.114c.316.118.573.213.82.363c.799.487.839.445 1.804.84c1.82.812 1.87 1.53 1.87 3.218c.037 1.214.105 3.159.152 3.97a.094.094 0 0 0 .1.09c1.223-.08 1.912-1.706 2.106-2.528l.785-2.97c.4-1.585.55-2.418.362-3.097c-.173-.625-.655-1.314-.833-1.527c0-.073.022-.207.05-.383c.096-.582.128-1.362-.186-2.07c-.503-1.05-1.258-1.313-1.781-1.461c-.477-.07-.764-.256-1.016-.781c-.992-1.794-2.234-1.696-2.805-1.696c-.461.055-.773.055-1.289-.297c-1.312-1.093-2.637-.703-3.423-.328c-.628.3-1.016.344-1.131.328c-.116.016-.505-.028-1.137-.328c-.789-.375-2.059-.797-3.45.328c-.46.399-.701.396-1.189.339c-.393-.047-1.97-.179-2.966 1.614c-.253.525-.717.62-.949.625c-.437.032-1.436.357-1.941 1.407c-.315.708-.225 1.746-.13 2.328c.029.175.05.31.05.383c-.178.213-.528.875-.702 1.5c-.188.678.088 2.34.308 3.117l.79 2.969c.195.823.842 2.444 2.07 2.524");
}

.kpi-j7bnf {
  stop-color: var(--svg-color--b7a9bb, #B7A9BB);
}

.kz8v_2b0u {
  stop-color: var(--svg-color--825c4f, #825C4F);
}

.l_hht1tza {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
  stop-opacity: 0;
}

.l_nupdb1h {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
}

.l235i7b0i {
  d: path("M8.528 5.592c.68-.51 1.791-.437 2.297-.297l1.11 6.61a5.7 5.7 0 0 1-2.485 1.64c-1.625-.86-2.125-3.562-2.125-5.078s.297-2.195 1.203-2.875");
}

.lba0g0b-f {
  stop-color: var(--svg-color--c78a71, #C78A71);
}

.lcus7p0ww {
  stop-color: var(--svg-color--faf9fc, #FAF9FC);
  stop-opacity: 0;
}

.ldsslmbvc {
  stop-color: var(--svg-color--b8779d, #B8779D);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmc_3jx7c {
  fill: var(--svg-color--cdcad1, #CDCAD1);
  d: path("m17.68 19.42l.001-.066a1.708 1.708 0 1 0-3.415.066h.55l-.001-.066a1.158 1.158 0 1 1 2.314.066z");
}

.lqfy3p-zi {
  stop-color: var(--svg-color--7a8488, #7A8488);
}

.lyk395t8a {
  d: path("M21.305 9.123V5.201c-.86-.171-1.047-.789-2.383-1.125c-1.086-.195-1.594.258-2.617.641v4.625c.663 1.647 2.365 2.619 3.469 3.028c.308.114.66.038.848-.232c.605-.867.683-2.198.683-3.015");
}

.lytc0obul {
  d: path("M23.093 18.928h-5.735c-.232 0-.418.199-.375.427c.318 1.723 1.717 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.879-.663-.879");
}

.m0j3jgbjt {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.947 24.215c-.958 0-1.86-.23-2.616-.634c-.26-.135-.537.163-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.539-.373-.404a5.54 5.54 0 0 1-2.617.634Z");
}

.m0wg8vbqd {
  fill: var(--svg-color--000, #000);
  d: path("M12.875 18.495a.937.937 0 0 0-.941-.94a.937.937 0 0 0-.94.94a.9.9 0 0 0 .104.433h1.665a.9.9 0 0 0 .112-.433");
}

.m1djvtbjd {
  stop-color: var(--svg-color--ce9692, #CE9692);
  stop-opacity: 0;
}

.m6yqys39r {
  d: path("M6.911 21.937a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.mceyoyhkc {
  d: path("M13.433 18.3c0-.53-.431-.883-.548-.99l-.53.513l.326.664z");
}

.md1neftgk {
  stop-color: var(--svg-color--bd8574, #BD8574);
}

.msq_ndbcs {
  stop-color: var(--svg-color--d39878, #D39878);
  stop-opacity: 0;
}

.mzc8gl1kv {
  d: path("M5.531 7.85c.969-.559 1.946-.447 2.313-.322l1.856 5.03c.126.278.45.756-.591 1.21c-1.1.48-1.704 1.303-1.938 1.768c-.05.099-.165.152-.257.092c-.843-.558-1.763-2.835-2.19-4.092c-.457-1.345-.403-2.986.807-3.685");
}

.mzycncwxb {
  stop-color: var(--svg-color--a33337, #A33337);
  stop-opacity: 0;
}

.n01394_5x {
  stop-color: var(--svg-color--c9d2d8, #C9D2D8);
  stop-opacity: 0;
}

.n292jgsxz {
  fill: var(--svg-color--d3a68d, #D3A68D);
  d: path("m15.243 18.194l-.978 2.97a.993.993 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.288l-.978-2.97c-.21-.694-1.188-.694-1.408 0");
}

.nb1ng5muw {
  stop-color: var(--svg-color--c48f74, #C48F74);
  stop-opacity: 0;
}

.nk5qlqb2c {
  stop-color: var(--svg-color--e1b6a1, #E1B6A1);
}

.nn382jjct {
  stop-color: var(--svg-color--c28962, #C28962);
}

.nt1lt3_he {
  stop-color: var(--svg-color--c48c7a, #C48C7A);
  stop-opacity: 0;
}

.ny7-5tbal {
  d: path("M21.429 18.277a1.54 1.54 0 0 0-.425-.85l-.478.524l.216.42z");
}

.nzscevbgj {
  stop-color: var(--svg-color--c3877e, #C3877E);
}

.o-gllcbpi {
  stop-color: var(--svg-color--c3c2c2, #C3C2C2);
}

.o0zfjub8g {
  stop-color: var(--svg-color--dbd9dd, #DBD9DD);
  stop-opacity: 0;
}

.o1xctu8tq {
  stop-color: var(--svg-color--f8f7fa, #F8F7FA);
}

.o6ackn6vy {
  stop-color: var(--svg-color--a33337, #A33337);
}

.o8-p00v9r {
  stop-color: var(--svg-color--b7a9bb, #B7A9BB);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op8gn6bnt {
  stop-color: var(--svg-color--c3c2c2, #C3C2C2);
  stop-opacity: 0;
}

.p_0c2tyib {
  stop-color: var(--svg-color--b8779d, #B8779D);
}

.p3ialubfs {
  d: path("M8.776 18.928h5.735c.232 0 .418.199.376.427c-.319 1.723-1.718 2.35-2.462 2.37l-1.922-.043c-1.425-.047-2.073-.986-2.39-1.875c-.17-.476.194-.879.663-.879");
}

.p9zg-objl {
  stop-color: var(--svg-color--b7e0ed, #B7E0ED);
  stop-opacity: 0;
}

.paruexevs {
  stop-color: var(--svg-color--d7d3db, #D7D3DB);
}

.pclqe2vzi {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.348 16.352c1.202 0 2.218.829 2.494 1.949a.505.505 0 0 1-.493.627h-4.106a.424.424 0 0 1-.418-.5a2.57 2.57 0 0 1 2.523-2.076");
}

.pew6frnzi {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
  stop-opacity: 0;
}

.pi9myibky {
  stop-color: var(--svg-color--d8dfe2, #D8DFE2);
}

.pidu3gbxk {
  d: path("M6.038 7.498a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.125H6.038z");
}

.pk4qrvtef {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.844 17.2c.117.157-.127.347-.405.555c-.278.207-.484.353-.6.197c-.117-.156.013-.451.29-.659c.278-.207.598-.249.715-.093");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pyimo2blq {
  fill: var(--svg-color--c7c7cd, #C7C7CD);
  fill-rule: evenodd;
  d: path("M22.788 19.319c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.q-py-xa8l {
  fill: var(--svg-color--c2c0c6, #C2C0C6);
  fill-rule: evenodd;
  d: path("M6.495 19.319c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.q270rhb2n {
  stop-color: var(--svg-color--b0a7b6, #B0A7B6);
}

.q612z752i {
  d: path("m6.77 21.263l.005.116c.227 5.159 4.255 8.623 9.172 8.623s8.945-3.464 9.172-8.622l.005-.111a.095.095 0 0 1-.076-.09c-.047-.81-.116-2.755-.152-3.968c0-1.688-.05-2.407-1.87-3.22a36 36 0 0 0-.57-.225c-.461-.18-.632-.247-1.235-.614c-.243-.147-.495-.242-.804-.358l-.015-.005q-.14-.051-.356-.114c-.907-.272-2.93-1.046-3.864-3.156c-.076-.17-.339-.18-.424-.014c-1.076 2.102-3.006 2.902-3.887 3.178q-.19.059-.32.106a4 4 0 0 0-.756.384a10 10 0 0 1-1.637.795c-1.258.555-2.069 1.523-2.12 3.242a153 153 0 0 1-.198 3.966a.1.1 0 0 1-.07.087");
}

.q63b76bcm {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
  stop-opacity: 0;
}

.q90nxab-j {
  stop-color: var(--svg-color--f7f5f9, #F7F5F9);
  stop-opacity: 0;
}

.qo6lmkbuu {
  fill-rule: evenodd;
  d: path("M6.495 19.319c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.qt6wr2b4a {
  stop-color: var(--svg-color--c28386, #C28386);
  stop-opacity: 0;
}

.r165x48_t {
  fill: var(--svg-color--85d7ed, #85D7ED);
  d: path("M8.776 18.928h5.735c.232 0 .418.199.376.427c-.319 1.723-1.718 2.35-2.462 2.37l-1.922-.043c-1.425-.047-2.073-.986-2.39-1.875c-.17-.476.194-.879.663-.879");
}

.r6b7ix18y {
  d: path("M22.735 19.91H17c-.232 0-.418.198-.375.427c.318 1.722 1.718 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.88-.663-.88");
}

.rwumr017n {
  stop-color: var(--svg-color--b46e8a, #B46E8A);
}

.s4m35hbub {
  stop-color: var(--svg-color--b78075, #B78075);
  stop-opacity: 0;
}

.s5l3r5b8v {
  d: path("M23.743 5.592c-.679-.51-1.791-.437-2.296-.297l-1.11 6.61a5.7 5.7 0 0 0 2.485 1.64c1.625-.86 2.125-3.562 2.125-5.078s-.297-2.195-1.204-2.875");
}

.senludb5g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.413 14.81c.354-.254 1.478-.724 3.14-.562");
}

.sjitiy62y {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
  stop-opacity: 0;
}

.spesxfync {
  stop-color: var(--svg-color--c48c7a, #C48C7A);
}

.suyfdv57p {
  stop-color: var(--svg-color--c78a71, #C78A71);
  stop-opacity: 0;
}

.t_fhyk9zs {
  stop-color: var(--svg-color--714c43, #714C43);
}

.t233yurnp {
  stop-color: var(--svg-color--c6c5c6, #C6C5C6);
}

.t6giq_bqy {
  stop-color: var(--svg-color--b87373, #B87373);
}

.tbow2ebjl {
  d: path("M8.419 19.91h5.734c.232 0 .418.198.376.427c-.319 1.722-1.718 2.35-2.462 2.37l-1.921-.043c-1.426-.047-2.074-.986-2.391-1.875c-.17-.476.194-.88.664-.88");
}

.tjn-pbcga {
  stop-color: var(--svg-color--b0a7b6, #B0A7B6);
  stop-opacity: 0;
}

.twp3ygv2w {
  stop-color: var(--svg-color--f7c39f, #F7C39F);
}

.tygkjs-ny {
  stop-color: var(--svg-color--9ca7ab, #9CA7AB);
  stop-opacity: 0;
}

.ubudbcc-l {
  stop-color: var(--svg-color--ce9692, #CE9692);
}

.ukdu4-bnh {
  stop-color: var(--svg-color--ac7763, #AC7763);
}

.unozt67tp {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
}

.uxt4me83a {
  d: path("M19.967 16.852a1.643 1.643 0 0 1 1.583 2.076h-3.173a1.7 1.7 0 0 1-.06-.433c0-.904.74-1.643 1.65-1.643");
}

.vfyzwablh {
  fill: var(--svg-color--85dbf1, #85DBF1);
  d: path("M23.093 18.928h-5.735c-.232 0-.418.199-.375.427c.318 1.723 1.717 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.879-.663-.879");
}

.vmhj67bpb {
  stop-color: var(--svg-color--c48b7b, #C48B7B);
  stop-opacity: 0;
}

.vn83tqcbo {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
}

.w-amzpbim {
  stop-color: var(--svg-color--d9d6dc, #D9D6DC);
  stop-opacity: 0;
}

.wokvbnbir {
  stop-color: var(--svg-color--e3b6a3, #E3B6A3);
  stop-opacity: 0;
}

.wpzk5jw3v {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.947 24.215c-.958 0-1.86-.23-2.616-.634c-.26-.135-.537.163-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.539-.373-.404a5.54 5.54 0 0 1-2.617.634");
}

.wskvwr48a {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.553 16.352a2.57 2.57 0 0 0-2.494 1.949a.505.505 0 0 0 .493.627h4.106c.262 0 .47-.239.418-.5a2.58 2.58 0 0 0-2.523-2.076");
}

.x6b7fvhjk {
  stop-color: var(--svg-color--e4e3e5, #E4E3E5);
  stop-opacity: 0;
}

.x6t_0e-6t {
  stop-color: var(--svg-color--c9d2d8, #C9D2D8);
}

.xcvhc4axz {
  stop-color: var(--svg-color--80cce7, #80CCE7);
}

.xh84v07wd {
  stop-color: var(--svg-color--b8e1ee, #B8E1EE);
  stop-opacity: 0;
}

.xuds1wbpf {
  stop-color: var(--svg-color--c28962, #C28962);
  stop-opacity: 0;
}

.yace-6bkn {
  stop-color: var(--svg-color--e4e3e5, #E4E3E5);
}

.yg9ra3bzd {
  stop-color: var(--svg-color--b7e0ed, #B7E0ED);
}

.ymq-6qbvn {
  stop-color: var(--svg-color--c38385, #C38385);
  stop-opacity: 0;
}

.z2ncl2bsp {
  stop-color: var(--svg-color--e3b6a3, #E3B6A3);
}

.z3bpdx_xu {
  stop-color: var(--svg-color--b78075, #B78075);
}

.za1tbsb_m {
  fill: var(--svg-color--252328, #252328);
  d: path("M18.049 17.782c.489-.86 1.231-1.538 2.83-1.538c.7 0 1.374.194 1.974.679c.495.4.429.911.046 1.103l-1.024.584c-1.2-.388-2.526-.44-3.826-.828");
}

.zcaxasb6b {
  d: path("m17.68 19.42l.001-.066a1.708 1.708 0 1 0-3.415.066h.55l-.001-.066a1.158 1.158 0 1 1 2.314.066z");
}

.zdciykbsu {
  fill: var(--svg-color--252328, #252328);
  d: path("M13.852 17.782c-.488-.86-1.231-1.538-2.83-1.538c-.7 0-1.374.194-1.974.679c-.495.4-.429.911-.046 1.103l1.024.584c1.2-.388 2.526-.44 3.826-.828");
}

.zf-dr2bxb {
  fill: var(--svg-color--87838b, #87838B);
  fill-rule: evenodd;
  d: path("M19.41 14.834c1.51-.274 2.56.224 2.844.457a.5.5 0 1 0 .635-.772c-.526-.433-1.878-.991-3.657-.67a.5.5 0 1 0 .178.985");
}

</style>
