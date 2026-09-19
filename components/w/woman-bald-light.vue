<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZ7TEhd)"><path fill="url(#imXqXWd)" class="pxmwf1ilj"/></g><g filter="url(#iC4V6UE)"><path fill="url(#iIgxxMb)" class="g14t4xb3k"/><path fill="url(#i9UuYME)" class="g14t4xb3k"/></g><g filter="url(#i3xIwJe)"><path class="swvrsib9j"/><path fill="url(#i4vPmJi)" class="us2srjd0a"/></g><g filter="url(#ituMKvv)"><path class="qsrxlcbzu"/><path fill="url(#iluKaje)" class="fz-7ddu-y"/></g><g filter="url(#iELsXMb)"><path fill="url(#iuyUlec)" class="jpek7pwna"/><path fill="url(#iJOVCpe)" class="jpek7pwna"/><path fill="url(#iZ2lgTc)" class="jpek7pwna"/><path fill="url(#iiz4aie)" class="jpek7pwna"/><path fill="url(#iEe1UUd)" class="jpek7pwna"/></g><path fill="url(#iTlQIJd)" class="jpek7pwna"/><path fill="url(#iv602qb)" class="jpek7pwna"/><g filter="url(#iJnENfg)"><path class="bmvbd4bgy"/></g><g filter="url(#iNL3hKe)"><path class="gvxczjtyc"/><path fill="url(#iE9iSue)" class="j-q6slbsb"/><path fill="url(#i83zJLc)" class="j-q6slbsb"/><path fill="url(#iCUCfQe)" class="j-q6slbsb"/><path fill="url(#i6guXDe)" class="j-q6slbsb"/></g><path fill="url(#iA8MQmr)" class="j-q6slbsb"/><path fill="url(#iompY0u)" class="j-q6slbsb"/><path stroke="url(#i2FXrqd)" class="skkzfdb9i"/><g filter="url(#i1p3Ylc)"><path class="zwd7wnb8n"/></g><g filter="url(#iwJt2Sb)"><path class="wzzdwob8h"/></g><path class="x7za0-ejn"/><path fill="url(#i8Vay1b)" class="dizhftb5m"/><path class="hnqgnjwxw"/><g filter="url(#i35Pskc)"><path class="ykxu4xwxt"/><path fill="url(#iphibuc)" class="l861-5p4t"/></g><g filter="url(#iEVBnZd)"><path fill="url(#ixjj5ne)" class="iju52fb9r"/></g><path class="c_rl6mbrh"/><path fill="url(#iQn7qFu)" class="c_b2a0iis"/><path class="x7bfp-sno"/><g filter="url(#i2d6ORs)"><path fill="url(#i9mdqgd)" class="ka2wzp4as"/></g><g filter="url(#iwyn5bc)"><ellipse transform="rotate(-27.914 11.478 16.515)" class="a342gudry"/><ellipse fill="url(#iRO7ohe)" transform="rotate(-27.914 11.478 16.515)" class="ghdxctbde"/></g><g filter="url(#ibX09Ce)"><path fill="url(#ieAd0Me)" class="kcci1kb3n"/></g><g filter="url(#i5MkTud)"><path class="icuae1ara"/></g><g filter="url(#i3JhGDd)"><path clip-rule="evenodd" class="uwfg7xphv"/></g><g filter="url(#iQsAk0b)"><path class="x25jcmbfn"/></g><g filter="url(#i3G4Owd)"><path class="eo-rawbiq"/></g><defs><radialGradient id="iIgxxMb" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.79687 4.63581 4.15888 24.459 19.626)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="i9UuYME" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 1.375 -.38873 .69354 25.505 14.673)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i4vPmJi" cx="0" cy="0" r="1" gradientTransform="matrix(2.81506 -.2094 .1637 2.2006 24.24 18.017)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iluKaje" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 0 0 -1.77497 7.474 17.807)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iuyUlec" cx="0" cy="0" r="1" gradientTransform="matrix(-9.375 5.12501 -6.13482 -11.2222 21.313 15.81)" gradientUnits="userSpaceOnUse"><stop class="i8xyi-54t"/><stop offset="1" class="s6dm7db8m"/></radialGradient><radialGradient id="iJOVCpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.60062 2.93086 0 11.595 15.815)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="xp5_7nbfc"/><stop offset="1" class="qqmab1ifr"/></radialGradient><radialGradient id="iZ2lgTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.60062 3.4675 0 20.636 15.65)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="tnby0uz1c"/><stop offset="1" class="y6a5lcbse"/></radialGradient><radialGradient id="iiz4aie" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03125 -1.93296 0 11.781 17.467)" gradientUnits="userSpaceOnUse"><stop class="lqcgjq2qs"/><stop offset="1" class="ra1c3f1wl"/><stop offset="1" class="x_x6uge6b"/></radialGradient><radialGradient id="iEe1UUd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93756 15.94082 -17.37414 -5.38152 19.188 12.998)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="pr6renx8i"/><stop offset="1" class="z0oer-bxh"/></radialGradient><radialGradient id="iTlQIJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8163 4.08668 -8.49893 3.7773 9.614 5.825)" gradientUnits="userSpaceOnUse"><stop class="hn3cf59bn"/><stop offset="1" class="edbrw3bas"/></radialGradient><radialGradient id="iv602qb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.10317 8.3385 -7.75702 -7.5381 24.103 6.669)" gradientUnits="userSpaceOnUse"><stop class="pvxj98t6e"/><stop offset="1" class="w49_p0iga"/></radialGradient><radialGradient id="iE9iSue" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.515 20.153)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="i6guXDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 17.068 20.548)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iompY0u" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5565 1.75513 -2.1094 -3.07252 16.755 19.438)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="i8Vay1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 20.12 16.694)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iphibuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.695 16.85)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQn7qFu" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.984 16.694)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRO7ohe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.143 2.915)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iZ7TEhd" width="6.15" height="6" x="4.316" y="14.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="iC4V6UE" width="6" height="6.25" x="22.052" y="14.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="i3xIwJe" width="5.005" height="5.005" x="22.55" y="15.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".25"/></filter><filter id="ituMKvv" width="4.805" height="4.805" x="4.95" y="15.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".2"/></filter><filter id="iELsXMb" width="19.853" height="24.601" x="6.699" y="4.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".25"/><feGaussianBlur stdDeviation=".875"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.682353 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="iJnENfg" width="4.5" height="5.719" x="13.423" y="16.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".25"/></filter><filter id="iNL3hKe" width="4" height="5.5" x="14.052" y="16.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".125"/></filter><filter id="i1p3Ylc" width="5.423" height="2.397" x="17.982" y="15.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="iwJt2Sb" width="5.423" height="2.397" x="8.7" y="15.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="i35Pskc" width="1.294" height="1.125" x="18.838" y="15.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".05"/></filter><filter id="iEVBnZd" width="1.316" height="1.357" x="20.491" y="16.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".1"/></filter><filter id="i2d6ORs" width="1.493" height="1.594" x="12.207" y="16.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".1"/></filter><filter id="iwyn5bc" width="1.529" height="1.141" x="10.713" y="15.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".05"/></filter><filter id="ibX09Ce" width="12.86" height="11.918" x="14.098" y="3.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation="1.25"/></filter><filter id="i5MkTud" width="4.4" height="1.861" x="8.952" y="12.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="i3JhGDd" width="4.4" height="1.861" x="19.052" y="12.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19260"/></filter><filter id="iQsAk0b" width="4.296" height="1.904" x="19.068" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".2"/></filter><filter id="i3G4Owd" width="4.296" height="1.904" x="8.904" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19260" stdDeviation=".2"/></filter><linearGradient id="imXqXWd" x1="4.316" x2="9.834" y1="17.97" y2="17.97" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="i83zJLc" x1="14.302" x2="16.052" y1="20.289" y2="20.289" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iCUCfQe" x1="16.052" x2="16.052" y1="21.779" y2="20.641" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iA8MQmr" x1="16.198" x2="16.198" y1="21.73" y2="21.47" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="i2FXrqd" x1="14.693" x2="15.537" y1="24.532" y2="22.907" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="ixjj5ne" x1="21.571" x2="20.986" y1="16.794" y2="17.155" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9mdqgd" x1="13.371" x2="12.786" y1="16.794" y2="17.155" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieAd0Me" x1="19.591" x2="25.45" y1="12.259" y2="4.945" gradientUnits="userSpaceOnUse"><stop class="a5lkoibji"/><stop offset="1" class="sfjtufb3d"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bald-light" /></template>
<style>
.a342gudry {
  cx: 11.478px;
  cy: 16.515px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.a5lkoibji {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bmvbd4bgy {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.244 17.61l-1.274 2.888a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.991-2.889c-.212-.702-.92-.702-1.142 0");
}

.c_b2a0iis {
  d: path("M11.98 15.805a1.664 1.664 0 0 0-1.603 2.102h3.214c.038-.144.06-.287.06-.439a1.675 1.675 0 0 0-1.67-1.663");
}

.c_rl6mbrh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.595 15.298c-1.218 0-2.247.84-2.527 1.974a.51.51 0 0 0 .5.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dizhftb5m {
  d: path("M20.124 15.805a1.664 1.664 0 0 1 1.604 2.102h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.edbrw3bas {
  stop-color: var(--svg-color--d3a68d, #D3A68D);
  stop-opacity: 0;
}

.eo-rawbiq {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.6 13.384c-.6-.147-2.096-.074-3.096.642");
}

.ft5dv1b6b {
  fill: none;
}

.fz-7ddu-y {
  d: path("M7.352 19.81a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.g14t4xb3k {
  d: path("M25.052 20.807a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.ghdxctbde {
  cx: 11.478px;
  cy: 16.515px;
  rx: 0.726px;
  ry: 0.368px;
}

.gvxczjtyc {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.34 17.134l-.992 3.17a1.005 1.005 0 0 0 .971 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.hn3cf59bn {
  stop-color: var(--svg-color--d3a68d, #D3A68D);
}

.hnqgnjwxw {
  fill: var(--svg-color--000, #000);
  d: path("M19.171 17.469a.95.95 0 0 1 .953-.954c.53 0 .953.424.953.953a.94.94 0 0 1-.106.44h-1.686a.86.86 0 0 1-.114-.44");
}

.i8xyi-54t {
  stop-color: var(--svg-color--ffddc1, #FFDDC1);
}

.icuae1ara {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m9.718 14.492l-.008.005h-.001a.5.5 0 0 1-.514-.858h.001l.002-.001l.006-.004l.017-.01a3 3 0 0 1 .277-.143c.184-.088.446-.2.765-.301c.633-.203 1.52-.373 2.476-.204a.5.5 0 0 1-.174.985c-.743-.132-1.457-.002-1.998.171a5 5 0 0 0-.85.36");
}

.iju52fb9r {
  d: path("M21.606 17.25a1.57 1.57 0 0 0-.431-.863l-.485.532l.22.425z");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j-q6slbsb {
  d: path("m15.34 17.134l-.992 3.17a1.005 1.005 0 0 0 .971 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.jpek7pwna {
  d: path("M6.699 20.205c.23 5.225 4.31 8.734 9.29 8.734c4.981 0 9.061-3.509 9.291-8.734l.021-8.722c0-3.3-2.057-5.92-6.3-6.735c-1.6-.212-4.5-.215-6 0c-4.242.815-6.3 3.435-6.3 6.735z");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.ka2wzp4as {
  d: path("M13.5 17.273c0-.538-.437-.896-.555-1.005l-.538.52l.331.674z");
}

.kcci1kb3n {
  d: path("m17.296 9.163l3.25-3.071c2.938 1.11 3.735 4.062 3.913 5.447l-5.041 1.39a2.227 2.227 0 0 1-2.122-3.766");
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l861-5p4t {
  d: path("M20.002 16.156c.118.159-.13.352-.411.563c-.282.21-.49.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqcgjq2qs {
  stop-color: var(--svg-color--e9b6a1, #E9B6A1);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr6renx8i {
  stop-color: var(--svg-color--b57994, #B57994);
  stop-opacity: 0;
}

.pvxj98t6e {
  stop-color: var(--svg-color--ffe5c4, #FFE5C4);
}

.pxmwf1ilj {
  d: path("M7.316 20.807a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qqmab1ifr {
  stop-color: var(--svg-color--d1968f, #D1968F);
  stop-opacity: 0;
}

.qsrxlcbzu {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M7.352 19.81a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.ra1c3f1wl {
  stop-color: var(--svg-color--d7a285, #D7A285);
  stop-opacity: 0;
}

.s6dm7db8m {
  stop-color: var(--svg-color--dca896, #DCA896);
}

.sfjtufb3d {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.skkzfdb9i {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.425 22.549a.34.34 0 0 0-.41.072a.32.32 0 0 0-.034.408a3.65 3.65 0 0 0 3.071 1.678a3.65 3.65 0 0 0 3.071-1.678a.33.33 0 0 0-.034-.412a.34.34 0 0 0-.41-.069a5.6 5.6 0 0 1-2.627.638a5.6 5.6 0 0 1-2.627-.637Z");
}

.swvrsib9j {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M25.052 19.81a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tnby0uz1c {
  stop-color: var(--svg-color--f9bbaa, #F9BBAA);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.us2srjd0a {
  d: path("M25.052 19.81a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.uwfg7xphv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m23.01 13.64l-.258.428za.5.5 0 0 1-.513.859l-.01-.006l-.04-.022a5 5 0 0 0-.809-.338c-.54-.173-1.254-.303-1.998-.171a.5.5 0 1 1-.174-.985c.957-.169 1.843.001 2.477.204a6 6 0 0 1 .98.41l.061.034l.018.01l.005.004h.002z");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w49_p0iga {
  stop-color: var(--svg-color--ffe5c4, #FFE5C4);
  stop-opacity: 0;
}

.wzzdwob8h {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.923 16.746c-.495-.87-1.247-1.558-2.866-1.558c-.709 0-1.393.197-2 .688c-.501.405-.434.923-.046 1.117l1.037.592c1.215-.393 2.559-.446 3.875-.839");
}

.x_x6uge6b {
  stop-color: var(--svg-color--e9b6a1, #E9B6A1);
  stop-opacity: 0;
}

.x25jcmbfn {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.668 13.384c.602-.147 2.097-.074 3.097.642");
}

.x7bfp-sno {
  fill: var(--svg-color--000, #000);
  d: path("M12.933 17.469a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.038.31.106.44h1.687a.95.95 0 0 0 .113-.44");
}

.x7za0-ejn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.51 15.298c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.159a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xp5_7nbfc {
  stop-color: var(--svg-color--d1968f, #D1968F);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y6a5lcbse {
  stop-color: var(--svg-color--f9bbaa, #F9BBAA);
  stop-opacity: 0;
}

.ykxu4xwxt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.002 16.156c.118.159-.13.352-.411.563c-.282.21-.49.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z0oer-bxh {
  stop-color: var(--svg-color--b57994, #B57994);
}

.zwd7wnb8n {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.182 16.746c.494-.87 1.247-1.558 2.866-1.558c.709 0 1.392.197 2 .688c.501.405.434.923.046 1.117l-1.037.592c-1.215-.393-2.559-.446-3.875-.839");
}

</style>
