<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iscfdzS)" class="tgxd0wrcd"/><path fill="url(#ik3v93d)" class="tgxd0wrcd"/><path fill="url(#i79QqRc)" class="tgxd0wrcd"/><path fill="url(#i0cI5nb)" class="tgxd0wrcd"/><path fill="url(#iwD20oN)" class="tgxd0wrcd"/><rect fill="url(#iEOBdQX)" class="udf-r2hzz"/><g filter="url(#iPDAxwR)"><circle fill="url(#iw19Vlc)" class="qg61o1a6m"/></g><g filter="url(#i1kYrqd)"><circle fill="url(#irAIZjc)" class="dtirt8tuk"/></g><g filter="url(#iIezQrb)"><circle fill="url(#iNKqrTo)" class="elc_j0b0h"/><circle fill="url(#ik8wsSb)" class="elc_j0b0h"/></g><g filter="url(#iyXrbqb)"><circle class="qzcj6bcdf"/><circle fill="url(#iKblgyd)" class="ky48d4byq"/><circle fill="url(#iKsZlSb)" class="ky48d4byq"/></g><g filter="url(#i9cvSpe)"><path fill="url(#izEyanb)" class="dg-kq41wt"/><path fill="url(#ie38uGj)" class="dg-kq41wt"/><path fill="url(#iyUtQBb)" class="dg-kq41wt"/><path fill="url(#iNfBUte)" class="dg-kq41wt"/><path fill="url(#iLlLR0b)" class="dg-kq41wt"/><path fill="url(#iU0QtMe)" class="dg-kq41wt"/></g><g filter="url(#iNq2o6b)"><path fill="url(#iO4JAdR)" class="kj57f1d4e"/></g><g filter="url(#idvH37v)"><path class="q866fhbcp"/><path fill="url(#iitsJ2t)" class="b7l21bb9k"/><path fill="url(#isVx2pa)" class="b7l21bb9k"/><path fill="url(#ifQzaab)" class="b7l21bb9k"/><path fill="url(#iSEflze)" class="b7l21bb9k"/></g><g filter="url(#iss7B3b)"><path class="p6z5_cciw"/></g><g filter="url(#igIXFtP)"><path class="f9evs2bje"/><path fill="url(#irvJyfc)" class="t1lzzdbjh"/><path fill="url(#iYlbqeb)" class="t1lzzdbjh"/><path fill="url(#in85Jnc)" class="t1lzzdbjh"/><path fill="url(#iug4S0c)" class="t1lzzdbjh"/></g><path fill="url(#iyQMI3c)" class="t1lzzdbjh"/><path class="eipshq-zc"/><path fill="url(#ibIOxLl)" class="ouun2dbnl"/><path class="g88988bsa"/><g filter="url(#ix7TU1d)"><path class="xr5cgcbxt"/><path fill="url(#iM7y8ed)" class="kn9d_r6zd"/></g><g filter="url(#iRQginb)"><path fill="url(#iRjHv3d)" class="bh9ztkbrf"/></g><path class="ii1ymeb_x"/><path fill="url(#iK8AMYb)" class="o3a_a8bqm"/><path class="xo-n_sbzb"/><g filter="url(#itHUdzd)"><path fill="url(#iaXk7ub)" class="kdo9fsbbt"/></g><g filter="url(#i3t2QLR)"><ellipse transform="rotate(-27.914 12.805 12.276)" class="rd27aeo8y"/><ellipse fill="url(#iCBlU3p)" transform="rotate(-27.914 12.805 12.276)" class="b2zg7lbnt"/></g><g filter="url(#itzLiQd)"><path stroke="url(#i4mynpc)" class="ndkx_np1s"/></g><g filter="url(#i5kH0Fn)"><path clip-rule="evenodd" class="hhbwbswee"/></g><g filter="url(#ipt18pc)"><path clip-rule="evenodd" class="fnqzki1au"/></g><g filter="url(#iXfBQXv)"><path class="f547-9o8v"/></g><g filter="url(#izqN6Jc)"><path class="be21uactl"/></g><g filter="url(#i299Exe)"><path stroke="url(#is2tPad)" clip-rule="evenodd" class="cz3e9pgnc"/><path stroke="url(#id9CqIc)" clip-rule="evenodd" class="cz3e9pgnc"/></g><path clip-rule="evenodd" class="v5gq4sb6o"/><defs><radialGradient id="iscfdzS" cx="0" cy="0" r="1" gradientTransform="rotate(160.481 9.326 14.092)scale(12.5328 12.8728)" gradientUnits="userSpaceOnUse"><stop class="ly599bb8t"/><stop offset=".578" class="sj3b9accl"/></radialGradient><radialGradient id="ik3v93d" cx="0" cy="0" r="1" gradientTransform="matrix(-20.8125 0 0 -13.0625 25.199 29.134)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="j7m096d8q"/><stop offset="1" class="t2in4vbqy"/></radialGradient><radialGradient id="i79QqRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.43107 5.625 0 10.836 30.214)" gradientUnits="userSpaceOnUse"><stop class="qew-7dtdq"/><stop offset="1" class="l3o3sjq6c"/></radialGradient><radialGradient id="iwD20oN" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61736 0 0 -2.43441 15.703 21.148)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="m97vr3bka"/><stop offset="1" class="mn2ubysev"/></radialGradient><radialGradient id="iEOBdQX" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 2.96875 -4.68169 4.04104 15.25 20.823)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="k1uf8vxjj"/><stop offset=".963" class="hcqj0acdc"/></radialGradient><radialGradient id="iw19Vlc" cx="0" cy="0" r="1" gradientTransform="matrix(2.27544 0 0 3.98204 7.668 13.284)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ik8wsSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07194 -.78054 .89089 1.22348 22.65 12.94)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iKblgyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.06488 -1.95862 1.14639 .62328 22.114 14.35)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iKsZlSb" cx="0" cy="0" r="1" gradientTransform="matrix(.3362 .3328 -.42902 .43342 22.168 13.284)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iyUtQBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.21287 -12.506 0 15.598 13.026)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iNfBUte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69482 2.08593 0 19.03 11.636)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iLlLR0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.80346 2.24277 0 13.12 11.592)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iitsJ2t" cx="0" cy="0" r="1" gradientTransform="matrix(1.03449 -3.83369 1.42165 .38362 21.623 7.96)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="isVx2pa" cx="0" cy="0" r="1" gradientTransform="matrix(4.95945 .4564 -.2454 2.66667 19.493 5.678)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ifQzaab" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.17729 -3.37201 0 15.989 2.131)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iSEflze" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 20.58 -6.169)scale(4.9415 7.74172)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iug4S0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2553 -.82025 0 16.413 15.367)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ibIOxLl" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05175 -1.67293 0 18.814 12.4)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iM7y8ed" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.322 1.72)scale(.49039 .67515)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iK8AMYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0518 -1.67301 0 13.157 12.4)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iCBlU3p" cx="0" cy="0" r="1" gradientTransform="matrix(-.01003 -.6405 .76991 -.01205 12.785 12.684)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="is2tPad" cx="0" cy="0" r="1" gradientTransform="matrix(-.08594 .28125 -1.54727 -.47278 16.265 17.436)" gradientUnits="userSpaceOnUse"><stop class="ilv7egb3p"/><stop offset="1" class="ykasb29iu"/></radialGradient><radialGradient id="id9CqIc" cx="0" cy="0" r="1" gradientTransform="matrix(.191 -.14453 .57285 .75707 14.332 17.753)" gradientUnits="userSpaceOnUse"><stop class="ilv7egb3p"/><stop offset="1" class="ykasb29iu"/></radialGradient><filter id="iPDAxwR" width="4.529" height="4.329" x="7.668" y="11.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21948"/></filter><filter id="i1kYrqd" width="3.58" height="3.58" x="8.042" y="11.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".25"/></filter><filter id="iIezQrb" width="4.579" height="4.579" x="20.003" y="10.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21948"/></filter><filter id="iyXrbqb" width="3.58" height="3.58" x="20.378" y="11.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".25"/></filter><filter id="i9cvSpe" width="13.451" height="15.846" x="9.301" y="5.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21948"/></filter><filter id="iNq2o6b" width="9.506" height="7.976" x="14.209" y="3.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation="1"/></filter><filter id="idvH37v" width="16.34" height="10.93" x="7.819" y="1.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21948"/></filter><filter id="iss7B3b" width="3.782" height="4.977" x="13.788" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".375"/></filter><filter id="igIXFtP" width="2.934" height="3.977" x="14.522" y="12.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".125"/></filter><filter id="ix7TU1d" width=".961" height=".843" x="17.892" y="11.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".05"/></filter><filter id="iRQginb" width="1.037" height="1.066" x="19.01" y="11.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".1"/></filter><filter id="itHUdzd" width="1.16" height="1.23" x="13.251" y="11.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".1"/></filter><filter id="i3t2QLR" width="1.124" height=".854" x="12.243" y="11.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".05"/></filter><filter id="itzLiQd" width="1.085" height="2.72" x="9.401" y="6.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".125"/></filter><filter id="i5kH0Fn" width="3.582" height="2.502" x="10.928" y="8.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.0235294 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21948"/></filter><filter id="ipt18pc" width="3.582" height="2.502" x="17.717" y="8.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.0235294 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21948"/></filter><filter id="iXfBQXv" width="3.282" height="2.052" x="10.953" y="9.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".2"/></filter><filter id="izqN6Jc" width="3.282" height="2.052" x="17.823" y="9.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".2"/></filter><filter id="i299Exe" width="3.695" height="1.445" x="14.082" y="16.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21948" stdDeviation=".05"/></filter><linearGradient id="i0cI5nb" x1="16" x2="16" y1="29.954" y2="29.369" gradientUnits="userSpaceOnUse"><stop class="ld3t7r4-o"/><stop offset="1" class="e_8zkvbjm"/></linearGradient><linearGradient id="irAIZjc" x1="9.832" x2="9.002" y1="13.646" y2="13.646" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iNKqrTo" x1="23.576" x2="22.515" y1="11.869" y2="15.158" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="izEyanb" x1="21.222" x2="11.32" y1="13.789" y2="15.265" gradientUnits="userSpaceOnUse"><stop class="dmvmvjbvi"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="ie38uGj" x1="8.992" x2="11.432" y1="17.285" y2="17.198" gradientUnits="userSpaceOnUse"><stop class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iU0QtMe" x1="16.026" x2="16.026" y1="-7.312" y2="21.848" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="iO4JAdR" x1="15.299" x2="25.859" y1="9.919" y2="6.138" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="irvJyfc" x1="14.868" x2="16.085" y1="14.644" y2="14.644" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iYlbqeb" x1="17.205" x2="15.876" y1="15.062" y2="15.043" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="in85Jnc" x1="16.241" x2="16.241" y1="16.025" y2="15.282" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iyQMI3c" x1="16.152" x2="16.152" y1="16.079" y2="15.862" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iRjHv3d" x1="19.822" x2="19.416" y1="12.47" y2="12.72" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaXk7ub" x1="14.121" x2="13.714" y1="12.47" y2="12.72" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4mynpc" x1="9.944" x2="9.944" y1="6.918" y2="9.715" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-frowning-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.b2zg7lbnt {
  cx: 12.805px;
  cy: 12.276px;
  rx: 0.505px;
  ry: 0.256px;
}

.b7l21bb9k {
  d: path("m22.237 4.885l.556.277c.974.484 1.53 1.59 1.322 2.766l-.765 3.942c-.068.407-.338.68-.742.69l-.023.001s.07-1.175.139-1.867c.056-.562-.042-.733-.556-1.245c-.279-.277-.487-.691-.487-1.106V7.236c0-.346-.279-.622-.557-.691c-.834-.208-2.573-.554-5.077-.554s-4.243.346-5.077.554c-.348.069-.557.345-.557.691v1.107c0 .415-.139.83-.487 1.106l-.208.208c-.278.207-.418.622-.418.968c.07.76.14 1.867.14 1.867q-.033 0-.064-.002a.82.82 0 0 1-.771-.69L7.84 7.86c-.14-1.107.417-2.213 1.39-2.697l.557-.277c.348-.208.696-.484 1.044-.76l1.252-1.315c.765-.691 1.877-.899 2.851-.415c.696.208 1.46.208 2.156 0c1.044-.345 2.226-.069 3.06.692l1.044 1.037c.278.346.626.553 1.043.76");
}

.be21uactl {
  stroke: var(--svg-color--323232, #323232);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.506 10.478a3.03 3.03 0 0 1-2.082-.852");
}

.bh9ztkbrf {
  d: path("M19.847 12.786a1.1 1.1 0 0 0-.3-.6l-.337.37l.152.296z");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cz3e9pgnc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.097 17.736c-.919-.628-1.93-.26-2.341.004a.275.275 0 0 1-.298-.462c.495-.319 1.766-.805 2.949.004a.275.275 0 0 1-.31.454Z");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dg-kq41wt {
  d: path("m9.376 12.49l.064.002s-.07-1.107-.14-1.867c0-.346.14-.761.418-.968l.209-.208c.347-.277.486-.691.486-1.106V7.236c0-.346.209-.622.557-.691c.834-.208 2.573-.554 5.077-.554s4.243.346 5.077.554c.279.069.557.345.557.691v1.107c0 .415.208.83.487 1.106c.65.456.61.707.556 1.245c-.07.691-.14 1.867-.14 1.867h.024l-.344 5.133c-.209 2.294-2.012 3.893-4.163 3.893h-4.163c-2.22 0-3.954-1.599-4.163-3.893z");
}

.dmvmvjbvi {
  stop-color: var(--svg-color--5a413e, #5A413E);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dtirt8tuk {
  cx: 9.832px;
  cy: 13.284px;
  r: 1.29px;
}

.e_8zkvbjm {
  stop-color: var(--svg-color--1b70c9, #1B70C9);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eipshq-zc {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.085 11.43a1.81 1.81 0 0 1 1.756 1.372a.355.355 0 0 1-.347.442h-2.892a.298.298 0 0 1-.295-.353a1.81 1.81 0 0 1 1.778-1.462");
}

.elc_j0b0h {
  cx: 22.168px;
  cy: 13.284px;
  r: 2.165px;
}

.f547-9o8v {
  stroke: var(--svg-color--323232, #323232);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.553 10.564c.656 0 1.441-.238 2.082-.852");
}

.f9evs2bje {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.493 12.914l-.689 2.204a.7.7 0 0 0 .675.907h1.02c.477 0 .815-.46.674-.907l-.689-2.204c-.147-.488-.836-.488-.991 0");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fnqzki1au {
  fill: var(--svg-color--121212, #121212);
  fill-rule: evenodd;
  d: path("M17.89 9.436a.625.625 0 0 0 .02.884a3.66 3.66 0 0 0 2.514 1.025a.625.625 0 1 0 0-1.25a2.4 2.4 0 0 1-1.65-.678a.625.625 0 0 0-.883.02");
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g88988bsa {
  fill: var(--svg-color--000, #000);
  d: path("M18.154 12.939a.66.66 0 0 1 .663-.663a.66.66 0 0 1 .588.967h-1.172a.6.6 0 0 1-.08-.305");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hcqj0acdc {
  stop-color: var(--svg-color--533c3d, #533C3D);
}

.hhbwbswee {
  fill: var(--svg-color--121212, #121212);
  fill-rule: evenodd;
  d: path("M14.087 9.436c.238.25.23.645-.02.884a3.66 3.66 0 0 1-2.514 1.025a.625.625 0 1 1 0-1.25a2.4 2.4 0 0 0 1.65-.678a.625.625 0 0 1 .884.02");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ii1ymeb_x {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.886 11.43a1.81 1.81 0 0 0-1.757 1.372a.355.355 0 0 0 .347.442h2.893a.298.298 0 0 0 .294-.353a1.816 1.816 0 0 0-1.777-1.462");
}

.ilv7egb3p {
  stop-color: var(--svg-color--564140, #564140);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7m096d8q {
  stop-color: var(--svg-color--3891c9, #3891C9);
  stop-opacity: 0;
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.k1uf8vxjj {
  stop-color: var(--svg-color--2b161b, #2B161B);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kdo9fsbbt {
  d: path("M14.211 12.803c0-.374-.304-.623-.386-.699l-.374.362l.23.468z");
}

.kj57f1d4e {
  d: path("m21.128 5.991l-3.99 1.33a1.358 1.358 0 0 0 .61 2.635l3.967-.532z");
}

.kn9d_r6zd {
  d: path("M18.732 12.026c.082.11-.09.245-.286.391s-.341.25-.424.14s.01-.319.206-.465s.421-.176.503-.066");
}

.ky48d4byq {
  cx: 22.168px;
  cy: 13.284px;
  r: 1.29px;
}

.l3o3sjq6c {
  stop-color: var(--svg-color--2683d3, #2683D3);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld3t7r4-o {
  stop-color: var(--svg-color--1b70c9, #1B70C9);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.ly599bb8t {
  stop-color: var(--svg-color--47b4ff, #47B4FF);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m97vr3bka {
  stop-color: var(--svg-color--045d9a, #045D9A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mn2ubysev {
  stop-color: var(--svg-color--045d9a, #045D9A);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ndkx_np1s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.111 7.046v1.163c-.01.193-.091.624-.335.807");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
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

.o3a_a8bqm {
  d: path("M13.154 11.782a1.157 1.157 0 0 0-1.115 1.461h2.235q.041-.149.042-.305a1.165 1.165 0 0 0-1.162-1.157");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ouun2dbnl {
  d: path("M18.817 11.782a1.157 1.157 0 0 1 1.114 1.461h-2.235q-.04-.149-.042-.305c0-.636.521-1.156 1.163-1.156");
}

.p6z5_cciw {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.632 13.126l-1.064 2.204c-.132.453.185.906.633.906h.956c.448 0 .765-.46.633-.906l-.646-2.204c-.139-.488-.367-.488-.512 0");
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q866fhbcp {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m22.237 4.885l.556.277c.974.484 1.53 1.59 1.322 2.766l-.765 3.942c-.068.407-.338.68-.742.69l-.023.001s.07-1.175.139-1.867c.056-.562-.042-.733-.556-1.245c-.279-.277-.487-.691-.487-1.106V7.236c0-.346-.279-.622-.557-.691c-.834-.208-2.573-.554-5.077-.554s-4.243.346-5.077.554c-.348.069-.557.345-.557.691v1.107c0 .415-.139.83-.487 1.106l-.208.208c-.278.207-.418.622-.418.968c.07.76.14 1.867.14 1.867q-.033 0-.064-.002a.82.82 0 0 1-.771-.69L7.84 7.86c-.14-1.107.417-2.213 1.39-2.697l.557-.277c.348-.208.696-.484 1.044-.76l1.252-1.315c.765-.691 1.877-.899 2.851-.415c.696.208 1.46.208 2.156 0c1.044-.345 2.226-.069 3.06.692l1.044 1.037c.278.346.626.553 1.043.76");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qew-7dtdq {
  stop-color: var(--svg-color--2683d3, #2683D3);
}

.qg61o1a6m {
  cx: 9.832px;
  cy: 13.284px;
  r: 2.165px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzcj6bcdf {
  cx: 22.168px;
  cy: 13.284px;
  r: 1.29px;
  fill: var(--svg-color--463133, #463133);
}

.rd27aeo8y {
  cx: 12.805px;
  cy: 12.276px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.505px;
  ry: 0.256px;
}

.sj3b9accl {
  stop-color: var(--svg-color--2e8bd7, #2E8BD7);
}

.t1lzzdbjh {
  d: path("m15.493 12.914l-.689 2.204a.7.7 0 0 0 .675.907h1.02c.477 0 .815-.46.674-.907l-.689-2.204c-.147-.488-.836-.488-.991 0");
}

.t2in4vbqy {
  stop-color: var(--svg-color--3891c9, #3891C9);
}

.tgxd0wrcd {
  d: path("M16 19.697c-5.502 0-9.963 4.46-9.963 9.963v.209h19.926v-.21c0-5.502-4.46-9.962-9.963-9.962");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.udf-r2hzz {
  width: 5.188px;
  height: 6.789px;
  x: 13.451px;
  y: 17.206px;
  rx: 2.594px;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v5gq4sb6o {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M17.097 17.736c-.919-.628-1.93-.26-2.341.004a.275.275 0 0 1-.298-.462c.495-.319 1.766-.805 2.949.004a.275.275 0 0 1-.31.454");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xo-n_sbzb {
  fill: var(--svg-color--000, #000);
  d: path("M13.817 12.939a.66.66 0 0 0-.663-.663a.66.66 0 0 0-.589.967h1.173a.66.66 0 0 0 .079-.305");
}

.xr5cgcbxt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.732 12.026c.082.11-.09.245-.286.391s-.341.25-.424.14s.01-.319.206-.465s.421-.176.503-.066");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ykasb29iu {
  stop-color: var(--svg-color--564140, #564140);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

</style>
