<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isjEz7b)"><path fill="url(#iEGRWdd)" class="pgxdggb8f"/><path fill="url(#imEkvwc)" class="pgxdggb8f"/></g><g filter="url(#iDus3pb)"><path class="nfz07jblm"/><path fill="url(#iw5htae)" class="sx_2bho4w"/><path fill="url(#i6JZ6gb)" class="sx_2bho4w"/></g><g filter="url(#i7P33Ne)"><path fill="url(#iXd3vad)" class="nlx0m8bul"/></g><g filter="url(#iPlhqNb)"><path fill="url(#ivg8LCH)" class="f7y0q3b8i"/></g><g filter="url(#ijq5zXd)"><path fill="url(#i4LG2Lb)" class="aftr1db4v"/><path fill="url(#ioAjDgc)" class="aftr1db4v"/><path fill="url(#ipYNY8e)" class="aftr1db4v"/><path fill="url(#ig8rPlc)" class="aftr1db4v"/><path fill="url(#irz4Yte)" class="aftr1db4v"/><path fill="url(#ipauF4c)" class="aftr1db4v"/><path fill="url(#iteLRGt)" class="aftr1db4v"/><path fill="url(#idoSOfb)" class="aftr1db4v"/></g><path fill="url(#iSwAzlc)" class="aftr1db4v"/><g filter="url(#ibhOOCc)"><path fill="url(#iKxjoqb)" class="lfhgbqbpe"/></g><g filter="url(#iPAXe1c)"><path class="v9za-1bbk"/></g><g filter="url(#ildKx5d)"><path class="ul7eocpet"/><path fill="url(#iRORaac)" class="suaaat_md"/><path fill="url(#i327Huc)" class="suaaat_md"/><path fill="url(#iDEtLvd)" class="suaaat_md"/><path fill="url(#icAApId)" class="suaaat_md"/></g><path class="hd134obzc"/><path fill="url(#iYvnpye)" class="ofu8fabwi"/><path fill="url(#i0ADr3d)" class="ofu8fabwi"/><g filter="url(#iyCpW2c)"><path class="tpvqc6fzo"/><path fill="url(#iiETAcd)" class="zvjc97brb"/><path fill="url(#iwAVf7b)" class="zvjc97brb"/><path fill="url(#i7RgrTb)" class="zvjc97brb"/></g><path stroke="url(#iEc0d0d)" class="l3gnt2bed"/><path class="elrym_w2b"/><path class="o2-b33bvz"/><rect fill="url(#i33dvOb)" class="sk5gp1bny"/><rect fill="url(#i2ymLke)" class="y-65e6b_r"/><path class="rxuxc_bss"/><path fill="url(#i6Roebd)" class="bkbt1ac_u"/><path class="wcvt0ac8v"/><g filter="url(#ieAaRFb)"><path fill="url(#ieSO6nb)" class="brueobcup"/></g><g filter="url(#ibRUKZc)"><ellipse transform="rotate(-27.914 11.516 16.814)" class="upn01uu3z"/><ellipse fill="url(#iILR3Kd)" transform="rotate(-27.914 11.516 16.814)" class="qswwy014y"/></g><path class="gt30jactz"/><path fill="url(#iBhMzwc)" class="y88jpuk8c"/><path class="jinan4fvw"/><g filter="url(#igEdKXc)"><path class="ot3oeljrj"/><path fill="url(#iHxZmbb)" class="uskb4jdtm"/></g><g filter="url(#iS8MBfd)"><path fill="url(#iDNhw8b)" class="ejovjgzrz"/></g><g filter="url(#i6pb4oe)"><path class="k68eogi1j"/></g><g filter="url(#iw8VQCb)"><path stroke="url(#ifsMPHe)" class="hcji4hbyf"/></g><g filter="url(#iOzCfCK)"><path class="k1pysr54e"/></g><g filter="url(#iUqogoW)"><path stroke="url(#iIOocsS)" class="xxlz6yb4g"/></g><defs><radialGradient id="imEkvwc" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 39.855 -30.613)scale(1.93052 2.20343)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iw5htae" cx="0" cy="0" r="1" gradientTransform="matrix(1.64694 -3.0292 1.773 .96396 24.87 19.741)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="i6JZ6gb" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 .5147 -.66351 .67031 24.954 18.094)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iXd3vad" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.094)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="i4LG2Lb" cx="0" cy="0" r="1" gradientTransform="rotate(152.026 9.333 10.293)scale(17.0552 31.3253)" gradientUnits="userSpaceOnUse"><stop class="nrl4dtbxe"/><stop offset="1" class="lzav1ju_h"/></radialGradient><radialGradient id="ioAjDgc" cx="0" cy="0" r="1" gradientTransform="rotate(158.66 12.363 6.765)scale(9.9616 12.7935)" gradientUnits="userSpaceOnUse"><stop class="j8pyuccba"/><stop offset="1" class="w4hrse86e"/></radialGradient><radialGradient id="ipYNY8e" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.625 3.09375 0 20.935 15.787)" gradientUnits="userSpaceOnUse"><stop class="ye4z6-b5j"/><stop offset="1" class="e5bbk1qcb"/></radialGradient><radialGradient id="ig8rPlc" cx="0" cy="0" r="1" gradientTransform="rotate(-90 13.909 2.159)scale(3.3125)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="oo9hszb8e"/><stop offset="1" class="y2t0nr67a"/></radialGradient><radialGradient id="irz4Yte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35307 -1.63196 1.28997 -1.85996 24.971 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="mvpnstb7h"/><stop offset="1" class="c_6lkqbdc"/></radialGradient><radialGradient id="ipauF4c" cx="0" cy="0" r="1" gradientTransform="rotate(127.136 .708 7.006)scale(2.8667 2.49422)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="bq36iubyr"/><stop offset="1" class="f4i4wtrkw"/></radialGradient><radialGradient id="iteLRGt" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.63513 0 17.688 4.13)" gradientUnits="userSpaceOnUse"><stop class="zo1y_ccja"/><stop offset="1" class="m_zq8_bma"/></radialGradient><radialGradient id="idoSOfb" cx="0" cy="0" r="1" gradientTransform="matrix(5.50258 5.98865 -10.42381 9.57777 7.94 4.505)" gradientUnits="userSpaceOnUse"><stop class="jsfzcsbqj"/><stop offset="1" class="l27sgm3pw"/></radialGradient><radialGradient id="iSwAzlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 26.0906 0 16.125 30.005)" gradientUnits="userSpaceOnUse"><stop class="lrofxebas"/><stop offset="1" class="csje6esze"/></radialGradient><radialGradient id="icAApId" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36044 -1.11102 0 16.745 21.086)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iYvnpye" cx="0" cy="0" r="1" gradientTransform="rotate(139.273 2.452 6.033)scale(4.16691 7.99724)" gradientUnits="userSpaceOnUse"><stop class="rlhs-hbwc"/><stop offset="1" class="xi80kbc0k"/></radialGradient><radialGradient id="i0ADr3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04688 -.9516 0 7.09 14.85)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l9fk14bxd"/><stop offset="1" class="uyez41bsl"/></radialGradient><radialGradient id="iiETAcd" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -2.09375 .72837 .69032 24.622 13.287)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="aq7827bba"/><stop offset="1" class="tco_4qs8v"/></radialGradient><radialGradient id="iwAVf7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 2.625 -2.01353 -1.12662 25.904 9.13)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wgw2105cx"/><stop offset="1" class="fj_enu3ru"/></radialGradient><radialGradient id="i7RgrTb" cx="0" cy="0" r="1" gradientTransform="matrix(.32886 -4.54687 .85753 .06202 26.841 16.38)" gradientUnits="userSpaceOnUse"><stop class="bddxqszam"/><stop offset="1" class="bwtw0srgi"/></radialGradient><radialGradient id="i6Roebd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.021 17.614)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="iILR3Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.309 3.046)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBhMzwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.158 17.614)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="iHxZmbb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.066 3.742)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="isjEz7b" width="6.553" height="6.553" x="21.802" y="14.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20110"/></filter><filter id="iDus3pb" width="4.991" height="4.991" x="22.459" y="15.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".25"/></filter><filter id="i7P33Ne" width="6.503" height="6.303" x="4.067" y="14.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20110"/></filter><filter id="iPlhqNb" width="4.991" height="4.991" x="4.723" y="15.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".25"/></filter><filter id="ijq5zXd" width="20.793" height="25.5" x="6.104" y="4.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.372549 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.498039 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_20110" result="effect2_innerShadow_3987_20110"/></filter><filter id="ibhOOCc" width="11.918" height="9.719" x="15.036" y="6.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation="1"/></filter><filter id="iPAXe1c" width="4.796" height="6.408" x="13.272" y="16.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".375"/></filter><filter id="ildKx5d" width="3.796" height="5.408" x="14.272" y="16.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".125"/></filter><filter id="iyCpW2c" width="4.3" height="9.2" x="23.17" y="7.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.568627 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20110"/></filter><filter id="ieAaRFb" width="1.493" height="1.594" x="12.245" y="16.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".1"/></filter><filter id="ibRUKZc" width="1.529" height="1.141" x="10.751" y="16.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".05"/></filter><filter id="igEdKXc" width="1.294" height="1.125" x="18.875" y="16.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".05"/></filter><filter id="iS8MBfd" width="1.316" height="1.357" x="20.528" y="16.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".1"/></filter><filter id="i6pb4oe" width="5.214" height="3" x="18.514" y="11.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20110"/></filter><filter id="iw8VQCb" width="4.458" height="2.061" x="18.789" y="12.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".2"/></filter><filter id="iOzCfCK" width="5.214" height="3" x="8.912" y="11.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20110"/></filter><filter id="iUqogoW" width="4.458" height="2.061" x="9.093" y="12.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20110" stdDeviation=".2"/></filter><linearGradient id="iEGRWdd" x1="27.005" x2="25.459" y1="16.034" y2="20.822" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="ivg8LCH" x1="7.218" x2="5.934" y1="18.653" y2="18.653" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iKxjoqb" x1="15.727" x2="30.915" y1="14.224" y2="8.787" gradientUnits="userSpaceOnUse"><stop class="mztcpwbis"/><stop offset="1" class="l_22_-0fa"/></linearGradient><linearGradient id="iRORaac" x1="14.652" x2="16.3" y1="20.064" y2="20.064" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="i327Huc" x1="17.818" x2="16.017" y1="20.655" y2="20.63" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iDEtLvd" x1="16.512" x2="16.512" y1="22.014" y2="20.965" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iEc0d0d" x1="14.236" x2="15.047" y1="24.955" y2="23.672" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i33dvOb" x1="13.17" x2="17.938" y1="8.149" y2="8.149" gradientUnits="userSpaceOnUse"><stop class="yvlcwfbeu"/><stop offset="1" class="xe91aacag"/></linearGradient><linearGradient id="i2ymLke" x1="13.313" x2="19.844" y1="10.528" y2="10.528" gradientUnits="userSpaceOnUse"><stop class="l15xm-bse"/><stop offset="1" class="ue66x-b9i"/></linearGradient><linearGradient id="ieSO6nb" x1="13.408" x2="12.823" y1="17.093" y2="17.453" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDNhw8b" x1="21.608" x2="21.023" y1="17.093" y2="17.453" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifsMPHe" x1="22.646" x2="19.154" y1="13.544" y2="13.544" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient><linearGradient id="iIOocsS" x1="13.147" x2="9.693" y1="12.683" y2="14.026" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-man-medium-dark" /></template>
<style>
.aftr1db4v {
  d: path("M15.27 4.505c-5.2 0-9.2 4.4-8.9 9.5l.8 10.4c.3 3.3 2.8 5.6 6 5.6h6c3.1 0 5.7-2.3 6-5.6l.7-10.4c.4-5.2-3.7-9.5-8.9-9.5z");
}

.aq7827bba {
  stop-color: var(--svg-color--8f8286, #8F8286);
}

.bddxqszam {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
}

.bkbt1ac_u {
  d: path("M12.018 16.103a1.664 1.664 0 0 0-1.604 2.102h3.215c.037-.143.06-.287.06-.438a1.675 1.675 0 0 0-1.671-1.665");
}

.bq36iubyr {
  stop-color: var(--svg-color--5d3734, #5D3734);
}

.brueobcup {
  d: path("M13.538 17.571c0-.538-.437-.896-.556-1.004l-.537.52l.33.673z");
}

.bwtw0srgi {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
  stop-opacity: 0;
}

.c_6lkqbdc {
  stop-color: var(--svg-color--764838, #764838);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.csje6esze {
  stop-color: var(--svg-color--7c4c57, #7C4C57);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.e5bbk1qcb {
  stop-color: var(--svg-color--855254, #855254);
  stop-opacity: 0;
}

.ejovjgzrz {
  d: path("M21.644 17.548a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.425z");
}

.elrym_w2b {
  fill: var(--svg-color--875a52, #875A52);
  d: path("M18.11 18.79a.5.5 0 0 1 .706.038c.195.218.377.37.612.474c.24.106.575.18 1.095.18a.5.5 0 0 1 0 1c-.612 0-1.094-.087-1.499-.265c-.409-.181-.701-.44-.954-.722a.5.5 0 0 1 .04-.706");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f4i4wtrkw {
  stop-color: var(--svg-color--5d3734, #5D3734);
  stop-opacity: 0;
}

.f7y0q3b8i {
  d: path("M7.218 20.09a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.fj_enu3ru {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gt30jactz {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.547 15.596c1.218 0 2.247.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.506a2.606 2.606 0 0 1 2.556-2.103");
}

.hcji4hbyf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.389 12.7c.883-.07 2.195.04 3.258.844");
}

.hd134obzc {
  fill: var(--svg-color--7f7680, #7F7680);
  d: path("M8.356 11.554a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.52a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.j8pyuccba {
  stop-color: var(--svg-color--9d7a6a, #9D7A6A);
}

.jinan4fvw {
  fill: var(--svg-color--000, #000);
  d: path("M19.209 17.767c0-.53.423-.953.953-.953s.953.423.953.953c0 .159-.038.31-.106.438h-1.687a.86.86 0 0 1-.113-.438");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jsfzcsbqj {
  stop-color: var(--svg-color--745b51, #745B51);
}

.k1pysr54e {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M12.951 13.005c-.71-.093-2.086-.078-3.164.813");
}

.k68eogi1j {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M19.389 13.005c.71-.093 2.086-.078 3.164.813");
}

.kwz2g5lgk {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
}

.l_22_-0fa {
  stop-color: var(--svg-color--a07c72, #A07C72);
  stop-opacity: 0;
}

.l15xm-bse {
  stop-color: var(--svg-color--684943, #684943);
}

.l27sgm3pw {
  stop-color: var(--svg-color--745b51, #745B51);
  stop-opacity: 0;
}

.l3gnt2bed {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.61 23.182a.335.335 0 0 0-.4.069a.305.305 0 0 0-.034.393a3.58 3.58 0 0 0 2.994 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.l9fk14bxd {
  stop-color: var(--svg-color--735551, #735551);
}

.lfhgbqbpe {
  d: path("m24.11 8.575l-5.739 1.914a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrofxebas {
  stop-color: var(--svg-color--7b406a, #7B406A);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lzav1ju_h {
  stop-color: var(--svg-color--74494d, #74494D);
}

.m_zq8_bma {
  stop-color: var(--svg-color--8d7063, #8D7063);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mv5v459od {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
  stop-opacity: 0;
}

.mvpnstb7h {
  stop-color: var(--svg-color--764838, #764838);
}

.mztcpwbis {
  stop-color: var(--svg-color--a07c72, #A07C72);
}

.nfz07jblm {
  fill: var(--svg-color--7a5654, #7A5654);
  d: path("M24.954 20.09a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nlx0m8bul {
  d: path("M7.218 21.246a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.nrl4dtbxe {
  stop-color: var(--svg-color--9b6c5f, #9B6C5F);
}

.o2-b33bvz {
  fill: var(--svg-color--6d4844, #6D4844);
  d: path("M13.335 18.817a.5.5 0 0 1 .724.69h-.001l-.002.002l-.004.004l-.011.012a2 2 0 0 1-.169.15a3.56 3.56 0 0 1-2.255.806a.5.5 0 1 1 0-1a2.56 2.56 0 0 0 1.718-.665");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8fabwi {
  d: path("M8.356 11.554a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.52a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.oo9hszb8e {
  stop-color: var(--svg-color--6f404d, #6F404D);
}

.ot3oeljrj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.04 16.454c.118.159-.13.352-.412.563s-.49.359-.609.2s.014-.458.296-.668s.606-.253.724-.095");
}

.pgxdggb8f {
  d: path("M24.954 21.246a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.qswwy014y {
  cx: 11.516px;
  cy: 16.814px;
  rx: 0.726px;
  ry: 0.368px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rlhs-hbwc {
  stop-color: var(--svg-color--bbb6b3, #BBB6B3);
}

.rxuxc_bss {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.632 15.596c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.506a2.61 2.61 0 0 0-2.556-2.103");
}

.sk5gp1bny {
  width: 6px;
  height: 1px;
  x: 13.17px;
  y: 7.149px;
  rx: 0.5px;
}

.suaaat_md {
  d: path("m15.567 17.614l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.655-.944-.7-1.244 0");
}

.sx_2bho4w {
  d: path("M24.954 20.09a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.tco_4qs8v {
  stop-color: var(--svg-color--8f8286, #8F8286);
  stop-opacity: 0;
}

.tpvqc6fzo {
  fill: var(--svg-color--9f9aa1, #9F9AA1);
  d: path("M23.904 11.554a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.997-1.071.997V13.48a1 1 0 0 0-.366-.774l-1.403-1.15z");
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ue66x-b9i {
  stop-color: var(--svg-color--7e5e56, #7E5E56);
}

.ul7eocpet {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.567 17.614l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.655-.944-.7-1.244 0");
}

.upn01uu3z {
  cx: 11.516px;
  cy: 16.814px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.uskb4jdtm {
  d: path("M20.04 16.454c.118.159-.13.352-.412.563s-.49.359-.609.2s.014-.458.296-.668s.606-.253.724-.095");
}

.uyez41bsl {
  stop-color: var(--svg-color--735551, #735551);
  stop-opacity: 0;
}

.v9za-1bbk {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.638 17.89l-1.571 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.9-3.1c-.227-.655-.429-.7-.729 0");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w4hrse86e {
  stop-color: var(--svg-color--9d7a6a, #9D7A6A);
  stop-opacity: 0;
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wcvt0ac8v {
  fill: var(--svg-color--000, #000);
  d: path("M12.97 17.767a.95.95 0 0 0-.952-.953a.95.95 0 0 0-.953.953c0 .159.037.31.106.438h1.686a.95.95 0 0 0 .114-.438");
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xe91aacag {
  stop-color: var(--svg-color--7a584d, #7A584D);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xi80kbc0k {
  stop-color: var(--svg-color--807680, #807680);
  stop-opacity: 0;
}

.xxlz6yb4g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.951 12.7c-.883-.07-2.195.04-3.258.844");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y-65e6b_r {
  width: 10px;
  height: 1px;
  x: 11.126px;
  y: 9.528px;
  rx: 0.5px;
}

.y2t0nr67a {
  stop-color: var(--svg-color--6f404d, #6F404D);
  stop-opacity: 0;
}

.y88jpuk8c {
  d: path("M20.162 16.103a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.67-1.664");
}

.ye4z6-b5j {
  stop-color: var(--svg-color--855254, #855254);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yvlcwfbeu {
  stop-color: var(--svg-color--6c4e44, #6C4E44);
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zo1y_ccja {
  stop-color: var(--svg-color--8d7063, #8D7063);
}

.zs1u76b3p {
  stop-color: var(--svg-color--5d4139, #5D4139);
}

.zvjc97brb {
  d: path("M23.904 11.554a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.997-1.071.997V13.48a1 1 0 0 0-.366-.774l-1.403-1.15z");
}

</style>
