<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="q4l-5eb6i"/><path fill="url(#ivVe5Oe)" class="ipec96tmp"/><path fill="url(#iykqu9g)" class="kxrpi4bvb"/><path fill="url(#ixqyT5d)" class="kxrpi4bvb"/><path fill="url(#itu7Eyc)" class="kxrpi4bvb"/><path fill="url(#iva0kve)" class="kxrpi4bvb"/><path fill="url(#iq2Ovjd)" class="kxrpi4bvb"/><path fill="url(#iyFysMd)" class="bhrtky2un"/><path fill="url(#igia1pV)" class="bhrtky2un"/><path fill="url(#iSQacDc)" class="bhrtky2un"/><path fill="url(#idSlKoc)" class="bhrtky2un"/><path fill="url(#iiylZ3d)" class="bhrtky2un"/><g filter="url(#i6lLKFb)"><path class="iaa62mhec"/></g><path fill="url(#i2EKeCb)" class="keezqubrb"/><path fill="url(#itaebhb)" class="keezqubrb"/><path fill="url(#iGe8yLe)" class="keezqubrb"/><g filter="url(#iULigSt)"><ellipse fill="url(#ixDTuwg)" transform="rotate(-29.74 28.333 11.212)" class="iqymxk8it"/></g><g filter="url(#ifCrYCc)"><path class="ggb3_7srx"/></g><g filter="url(#iDRRuQe)"><path fill="url(#iWg6Pue)" class="zrl62jbaz"/></g><path fill="url(#ip0ByDq)" class="v3g_ucccc"/><path fill="url(#itaQKhb)" class="v3g_ucccc"/><path fill="url(#iQ3hsUb)" class="v3g_ucccc"/><path fill="url(#i7aWlWb)" class="v3g_ucccc"/><path fill="url(#ihXmh1b)" class="jttrnwbqg"/><path fill="url(#iRF9Fuc)" class="jttrnwbqg"/><g filter="url(#iotbusd)"><path class="yoa76u7in"/></g><g filter="url(#ie3ExWd)"><path stroke="url(#it7qZIl)" class="vlqxrnbqv"/></g><g filter="url(#ihI6zPb)"><path stroke="url(#iIko7Mc)" class="w6-_-3dda"/></g><g filter="url(#iAm3XGd)"><path class="kqv9a7isk"/><path stroke="url(#ibHNhfr)" class="ktlux6b4h"/></g><g filter="url(#iieGz6b)"><path class="kgb-q4bls"/><path stroke="url(#iEm1Nzd)" class="x_fqzbc7n"/></g><path stroke="url(#iYEuAzd)" class="jtz1nhbbo"/><path stroke="url(#iUSyQtc)" class="jtz1nhbbo"/><path stroke="url(#i3HnY7w)" class="o4i6k7cfk"/><path stroke="url(#i9gbvIb)" class="o4i6k7cfk"/><g filter="url(#iCFf6ke)"><path class="yc775letb"/></g><g filter="url(#iJEPHod)"><path stroke="url(#iSaekyc)" class="i2v9erf1b"/></g><g filter="url(#iKufhDl)"><path class="b74jdtb8a"/></g><defs><radialGradient id="ivVe5Oe" cx="0" cy="0" r="1" gradientTransform="rotate(99.083 5.774 17.35)scale(15.8773 17.7696)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="b789c5tod"/><stop offset="1" class="hmh1-6bsw"/></radialGradient><radialGradient id="iykqu9g" cx="0" cy="0" r="1" gradientTransform="rotate(156.037 10.516 8.041)scale(4.10207 8.61847)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="sdk-7abqu"/><stop offset="1" class="nrkg-hbuk"/></radialGradient><radialGradient id="ixqyT5d" cx="0" cy="0" r="1" gradientTransform="rotate(154.952 10.46 8.157)scale(5.1506 12.9593)" gradientUnits="userSpaceOnUse"><stop offset=".769" class="f3n-qdb9e"/><stop offset="1" class="ad__9qbkg"/></radialGradient><radialGradient id="iva0kve" cx="0" cy="0" r="1" gradientTransform="rotate(-127.591 15.968 1.303)scale(3.72686 .79712)" gradientUnits="userSpaceOnUse"><stop class="xibcskisp"/><stop offset="1" class="yfevfjb4h"/></radialGradient><radialGradient id="iq2Ovjd" cx="0" cy="0" r="1" gradientTransform="rotate(84.463 6.713 13.77)scale(2.29203 2.86609)" gradientUnits="userSpaceOnUse"><stop class="z2lq_sbqg"/><stop offset="1" class="essb3qbce"/></radialGradient><radialGradient id="iyFysMd" cx="0" cy="0" r="1" gradientTransform="rotate(146.452 5.733 10.183)scale(3.50589 9.38314)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="q0axu6bfj"/><stop offset="1" class="z_zoucbsi"/></radialGradient><radialGradient id="igia1pV" cx="0" cy="0" r="1" gradientTransform="matrix(-3.875 2.43748 -6.52366 -10.37103 16.138 15.501)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="kkt76lblo"/><stop offset="1" class="mujap9bhi"/></radialGradient><radialGradient id="iSQacDc" cx="0" cy="0" r="1" gradientTransform="rotate(-32.681 36.066 -13.194)scale(3.93552 24.9102)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="ixa02swnp"/><stop offset="1" class="jiqnz5bop"/></radialGradient><radialGradient id="iiylZ3d" cx="0" cy="0" r="1" gradientTransform="matrix(.27556 2.28608 -2.69994 .32545 12.91 11.11)" gradientUnits="userSpaceOnUse"><stop class="z2lq_sbqg"/><stop offset="1" class="essb3qbce"/></radialGradient><radialGradient id="i2EKeCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -5.14062 2.21896 .48561 25.7 17.814)" gradientUnits="userSpaceOnUse"><stop class="z06a1xbjg"/><stop offset="1" class="yg4a90uxw"/></radialGradient><radialGradient id="itaebhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.04687 .10937 -.38691 3.7033 24.981 11.532)" gradientUnits="userSpaceOnUse"><stop class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iGe8yLe" cx="0" cy="0" r="1" gradientTransform="rotate(-115.643 20.287 -.877)scale(8.26823 5.73683)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="yz9yob3rx"/><stop offset="1" class="s1ie74k7g"/></radialGradient><radialGradient id="ixDTuwg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69946 .39095 -.54292 -2.3601 28.953 11.215)" gradientUnits="userSpaceOnUse"><stop class="ripzkxbcm"/><stop offset="1" class="nc9smn6vd"/></radialGradient><radialGradient id="iWg6Pue" cx="0" cy="0" r="1" gradientTransform="rotate(113.948 8.679 19.112)scale(12.2413 6.11907)" gradientUnits="userSpaceOnUse"><stop class="pgj76mb-f"/><stop offset="1" class="oaopunb0a"/></radialGradient><radialGradient id="ip0ByDq" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74425 2.16183 -5.117 -8.86255 19.11 12.38)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="uo9lf0byt"/><stop offset="1" class="ld46n1b1m"/></radialGradient><radialGradient id="itaQKhb" cx="0" cy="0" r="1" gradientTransform="rotate(155.037 8.473 8.252)scale(1.99927 7.66345)" gradientUnits="userSpaceOnUse"><stop class="trf1vsb5x"/><stop offset="1" class="msvat0c6l"/></radialGradient><radialGradient id="i7aWlWb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 2.5 -2.76076 .31059 15.615 6.573)" gradientUnits="userSpaceOnUse"><stop class="z2lq_sbqg"/><stop offset="1" class="essb3qbce"/></radialGradient><radialGradient id="ihXmh1b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15624 .96876 -3.28463 -3.9203 14.481 18.439)" gradientUnits="userSpaceOnUse"><stop class="qksy-_bdp"/><stop offset="1" class="tcjp-hb-z"/></radialGradient><radialGradient id="iRF9Fuc" cx="0" cy="0" r="1" gradientTransform="matrix(.2813 2.1063 -2.74727 .36691 11.289 15.764)" gradientUnits="userSpaceOnUse"><stop class="z2lq_sbqg"/><stop offset="1" class="essb3qbce"/></radialGradient><radialGradient id="ibHNhfr" cx="0" cy="0" r="1" gradientTransform="matrix(1.54687 -1.53125 3.91781 3.95778 23.013 5.36)" gradientUnits="userSpaceOnUse"><stop class="kzdh98h8q"/><stop offset=".744" class="t68_d7h5n"/></radialGradient><radialGradient id="iEm1Nzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6667 -1.60486 4.1034 4.26156 20.998 7.075)" gradientUnits="userSpaceOnUse"><stop class="kzdh98h8q"/><stop offset=".862" class="t68_d7h5n"/></radialGradient><radialGradient id="iUSyQtc" cx="0" cy="0" r="1" gradientTransform="rotate(164.814 1.924 9.775)scale(2.26665 6.09358)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l96_08dtf"/><stop offset="1" class="mes48ob5k"/></radialGradient><radialGradient id="i9gbvIb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08905 .55293 -1.45444 -5.4951 4.346 20.392)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l96_08dtf"/><stop offset="1" class="mes48ob5k"/></radialGradient><filter id="i6lLKFb" width="5.595" height="8.26" x="12.105" y="11.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".375"/></filter><filter id="iULigSt" width="2.735" height="3.069" x="26.966" y="9.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".25"/></filter><filter id="ifCrYCc" width="6.259" height="7.813" x="23.074" y="14.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".5"/></filter><filter id="iDRRuQe" width="6.88" height="14" x="23.45" y="15.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".75"/></filter><filter id="iotbusd" width="11.875" height="11.063" x="13.169" y="13.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".75"/></filter><filter id="ie3ExWd" width="7.072" height="11.259" x="18.281" y="5.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".6"/></filter><filter id="ihI6zPb" width="4.444" height="6.709" x="20.259" y="9.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".35"/></filter><filter id="iAm3XGd" width="5.549" height="6.363" x="20.531" y="1.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.337255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1139"/></filter><filter id="iieGz6b" width="5.902" height="6.621" x="18.359" y="3.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.337255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1139"/></filter><filter id="iCFf6ke" width="5.285" height="6.928" x="10.515" y="16.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".375"/></filter><filter id="iJEPHod" width="6.281" height="10.797" x="14.669" y="6.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".5"/></filter><filter id="iKufhDl" width="2.688" height="2.59" x="18.169" y="15.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1139" stdDeviation=".25"/></filter><linearGradient id="itu7Eyc" x1="20.715" x2="20.309" y1="16.559" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="zzirkubdu"/><stop offset="1" class="npkqqr1mk"/></linearGradient><linearGradient id="idSlKoc" x1="16.982" x2="15.263" y1="19.251" y2="18.345" gradientUnits="userSpaceOnUse"><stop class="zzirkubdu"/><stop offset="1" class="npkqqr1mk"/></linearGradient><linearGradient id="iQ3hsUb" x1="17.825" x2="16.966" y1="17.86" y2="15.22" gradientUnits="userSpaceOnUse"><stop class="zzirkubdu"/><stop offset="1" class="npkqqr1mk"/></linearGradient><linearGradient id="it7qZIl" x1="24.825" x2="20.2" y1="16.314" y2="6.939" gradientUnits="userSpaceOnUse"><stop class="we_r89xyw"/><stop offset="1" class="yb9ear3ix"/></linearGradient><linearGradient id="iIko7Mc" x1="23.669" x2="21.2" y1="14.689" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="hntnklbqk"/><stop offset="1" class="shhwhm3pl"/></linearGradient><linearGradient id="iYEuAzd" x1="5.638" x2="8.825" y1="16.087" y2="22.72" gradientUnits="userSpaceOnUse"><stop class="norwhxbmc"/><stop offset="1" class="ez4l67b7b"/></linearGradient><linearGradient id="i3HnY7w" x1="3.674" x2="7.416" y1="17.954" y2="26.075" gradientUnits="userSpaceOnUse"><stop offset=".298" class="norwhxbmc"/><stop offset="1" class="ez4l67b7b"/></linearGradient><linearGradient id="iSaekyc" x1="18.999" x2="15.443" y1="13.951" y2="8.551" gradientUnits="userSpaceOnUse"><stop class="ekvhdtbxp"/><stop offset="1" class="ekvhdtbxp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waving-hand-medium-dark" /></template>
<style>
.ad__9qbkg {
  stop-color: var(--svg-color--693a35, #693A35);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b74jdtb8a {
  stroke: var(--svg-color--93746c, #93746C);
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.044 16.84c.27-.195.558-.414.937-.84");
}

.b789c5tod {
  stop-color: var(--svg-color--7a3f68, #7A3F68);
  stop-opacity: 0;
}

.bhrtky2un {
  d: path("M10.734 14.219a2.067 2.067 0 0 1 3.514-2.03c1.034 2.085 2.308 4.518 3.276 5.937c-1.23 1.672-1.526 2.516-1.78 3.234c-.782-1.088-2.416-3.304-3-4.046c-.314-.398-.696-.907-1.09-1.008a13 13 0 0 1-.92-2.087");
}

.ekvhdtbxp {
  stop-color: var(--svg-color--95756d, #95756D);
}

.essb3qbce {
  stop-color: var(--svg-color--8b6d5f, #8B6D5F);
  stop-opacity: 0;
}

.ez4l67b7b {
  stop-color: var(--svg-color--0d5194, #0D5194);
}

.f3n-qdb9e {
  stop-color: var(--svg-color--693a35, #693A35);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ggb3_7srx {
  fill: var(--svg-color--906660, #906660);
  d: path("M28.333 19.376a4.505 4.505 0 0 1-3.5-4.062c-.469.208-1 1.859-.64 2.968c.702 2.17 2.984 2.823 3.609 2.844z");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.hmh1-6bsw {
  stop-color: var(--svg-color--7a3f68, #7A3F68);
}

.hntnklbqk {
  stop-color: var(--svg-color--907067, #907067);
}

.i2v9erf1b {
  stroke-linecap: round;
  d: path("M16.169 8.376c.323 1.125 1.76 5.365 3.281 7.797");
}

.iaa62mhec {
  fill: var(--svg-color--9c7a70, #9C7A70);
  d: path("M16.346 19.392c-1.701-2.814-2.796-4.85-3.41-5.896a.577.577 0 0 1 .167-.769a.555.555 0 0 1 .792.182l1.369 2.378l1.686 3.058c-.187.5-.406.89-.604 1.047");
}

.ipec96tmp {
  d: path("M19.314 6.09a2.09 2.09 0 0 1 2.01 1.518c.8 2.322 2.25 5.629 3.327 7.123c.19-.493.329-1.11.389-1.652c.02-.188.152-1.41.336-1.956c.221-.658.678-1.225 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.052.162.08.326c.13.56.04 1.073-.014 1.412a61 61 0 0 0-.359 2.625a19.6 19.6 0 0 0 .125 4.78c.3 1.413.219 2.912.14 3.485c-.86 6.311-7.847 6.782-9.812 5.85c-1.339-.434-2.758-1.47-4.71-3.467c-2.283-2.335-4.368-4.905-5.529-6.643a2.067 2.067 0 0 1 2.276-3.216c-.376-.735-.68-1.377-.917-2.087a2.067 2.067 0 0 1 3.534-2.007c-.12-.267-.835-2.032-.96-2.855a2.089 2.089 0 0 1 6.01-3.266");
}

.iqymxk8it {
  cx: 28.333px;
  cy: 11.212px;
  rx: 0.773px;
  ry: 1.106px;
}

.ixa02swnp {
  stop-color: var(--svg-color--5e3a2e, #5E3A2E);
  stop-opacity: 0;
}

.jiqnz5bop {
  stop-color: var(--svg-color--5e3a2e, #5E3A2E);
}

.jttrnwbqg {
  d: path("M11.647 16.305a2.067 2.067 0 0 0-2.276 3.216c1.004 1.504 2.7 3.63 4.616 5.687c2.378-1.114 2.166-3.379 1.76-3.86c-.007.021-2.024-2.79-3.004-4.034l-.049-.062c-.303-.387-.666-.85-1.04-.946c-.145-.265-.146-.273-.007 0");
}

.jtz1nhbbo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M4.548 16.087c-.2 2.469 1.191 5.219 4.675 5.797");
}

.keezqubrb {
  d: path("m24.647 14.725l.004.006a7 7 0 0 0 .389-1.652l.002-.018c.026-.238.156-1.407.334-1.938c.221-.658.678-1.225 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.052.162.08.326c.126.538.047 1.034-.007 1.372l-.006.04a61 61 0 0 0-.36 2.625c-.094.9-.153 2.327.02 3.966c-2.27.437-3.664-.998-4.135-1.826c-.509-.895-.614-2.597-.395-2.932");
}

.kgb-q4bls {
  stroke: var(--svg-color--1b99e7, #1B99E7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M18.81 4.099c1.75.058 5.015 1.574 4.898 5.62");
}

.kkt76lblo {
  stop-color: var(--svg-color--6d4138, #6D4138);
  stop-opacity: 0;
}

.kqv9a7isk {
  stroke: var(--svg-color--1b99e7, #1B99E7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M20.981 2.52c1.758.126 4.64 1.598 4.547 5.364");
}

.ktlux6b4h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M20.981 2.52c1.758.126 4.64 1.598 4.547 5.364");
}

.kxrpi4bvb {
  d: path("M17.225 8.154c.029.248.102.567.251.956c.066.17.145.388.238.644c.445 1.22 1.206 3.308 2.25 5.21c.393.716 1.11 1.22 1.927 1.181c1.076-.05 2.312-.405 2.786-1.464l-.003-.01l-.023.06c-1.077-1.495-2.527-4.8-3.327-7.123a2.09 2.09 0 0 0-4.099.546");
}

.kzdh98h8q {
  stop-color: var(--svg-color--16579c, #16579C);
}

.l96_08dtf {
  stop-color: var(--svg-color--0e5196, #0E5196);
  stop-opacity: 0;
}

.ld46n1b1m {
  stop-color: var(--svg-color--62362f, #62362F);
}

.mes48ob5k {
  stop-color: var(--svg-color--0e5196, #0E5196);
}

.msvat0c6l {
  stop-color: var(--svg-color--6c413a, #6C413A);
  stop-opacity: 0;
}

.mujap9bhi {
  stop-color: var(--svg-color--6d4138, #6D4138);
}

.nc9smn6vd {
  stop-color: var(--svg-color--a17d72, #A17D72);
  stop-opacity: 0;
}

.norwhxbmc {
  stop-color: var(--svg-color--1679c5, #1679C5);
}

.npkqqr1mk {
  stop-color: var(--svg-color--8a5d5b, #8A5D5B);
  stop-opacity: 0;
}

.nrkg-hbuk {
  stop-color: var(--svg-color--724448, #724448);
}

.o4i6k7cfk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M2.638 17.954c-.235 2.469 1.398 4.985 4.46 5.399");
}

.oaopunb0a {
  stop-color: var(--svg-color--a57f74, #A57F74);
  stop-opacity: 0;
}

.pgj76mb-f {
  stop-color: var(--svg-color--a57f74, #A57F74);
}

.q0axu6bfj {
  stop-color: var(--svg-color--7f5056, #7F5056);
  stop-opacity: 0;
}

.q4l-5eb6i {
  fill: var(--svg-color--8a5d5b, #8A5D5B);
  d: path("M19.314 6.09a2.09 2.09 0 0 1 2.01 1.518c.8 2.322 2.25 5.629 3.327 7.123c.19-.493.329-1.11.389-1.652c.02-.188.152-1.41.336-1.956c.221-.658.678-1.225 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.052.162.08.326c.13.56.04 1.073-.014 1.412a61 61 0 0 0-.359 2.625a19.6 19.6 0 0 0 .125 4.78c.3 1.413.219 2.912.14 3.485c-.86 6.311-7.847 6.782-9.812 5.85c-1.339-.434-2.758-1.47-4.71-3.467c-2.283-2.335-4.368-4.905-5.529-6.643a2.067 2.067 0 0 1 2.276-3.216c-.376-.735-.68-1.377-.917-2.087a2.067 2.067 0 0 1 3.534-2.007c-.12-.267-.835-2.032-.96-2.855a2.089 2.089 0 0 1 6.01-3.266");
}

.qksy-_bdp {
  stop-color: var(--svg-color--7e554b, #7E554B);
}

.ripzkxbcm {
  stop-color: var(--svg-color--a17d72, #A17D72);
}

.s1ie74k7g {
  stop-color: var(--svg-color--7d6159, #7D6159);
}

.sdk-7abqu {
  stop-color: var(--svg-color--724448, #724448);
  stop-opacity: 0;
}

.shhwhm3pl {
  stop-color: var(--svg-color--907067, #907067);
  stop-opacity: 0;
}

.t68_d7h5n {
  stop-color: var(--svg-color--16579c, #16579C);
  stop-opacity: 0;
}

.tcjp-hb-z {
  stop-color: var(--svg-color--7e554b, #7E554B);
  stop-opacity: 0;
}

.trf1vsb5x {
  stop-color: var(--svg-color--6c413a, #6C413A);
}

.uo9lf0byt {
  stop-color: var(--svg-color--62362f, #62362F);
  stop-opacity: 0;
}

.v3g_ucccc {
  d: path("M14.163 11.973c.745 1.6 1.672 3.594 2.832 5.314c.207.308.58.465.924.326a5.2 5.2 0 0 0 2.047-1.543c.238-.296.23-.71.045-1.042c-.842-1.504-2.043-4.165-2.799-6.875a2.067 2.067 0 0 0-3.908 1.204c.104.689.623 2.038.859 2.616");
}

.vlqxrnbqv {
  stroke-linecap: round;
  d: path("M19.981 7.282c.532 2.282 2.516 6.079 3.672 7.86");
}

.w6-_-3dda {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-7px, 0.7px);
  d: path("M21.31 10.33c.343.801 1.168 2.909 2.343 4.609");
}

.we_r89xyw {
  stop-color: var(--svg-color--93726b, #93726B);
}

.x_fqzbc7n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M18.81 4.099c1.75.058 5.015 1.574 4.898 5.62");
}

.xibcskisp {
  stop-color: var(--svg-color--66463c, #66463C);
}

.yb9ear3ix {
  stop-color: var(--svg-color--a27e73, #A27E73);
}

.yc775letb {
  fill: var(--svg-color--9c7a70, #9C7A70);
  d: path("M14.908 22.785a54 54 0 0 1-3.514-4.318a.696.696 0 0 1 .14-.953a.72.72 0 0 1 1.011.112l2.504 3.112c.012.9-.09 1.74-.141 2.047");
}

.yfevfjb4h {
  stop-color: var(--svg-color--66463c, #66463C);
  stop-opacity: 0;
}

.yg4a90uxw {
  stop-color: var(--svg-color--895a5c, #895A5C);
  stop-opacity: 0;
}

.yoa76u7in {
  fill: var(--svg-color--80574f, #80574F);
  d: path("M14.684 22.474a.5.5 0 1 0 .97.242zm8.427-6.446a.5.5 0 0 0-.134-.991zm-7.457 6.688c.278-1.113 1.361-2.689 2.822-4.062c1.459-1.37 3.178-2.428 4.635-2.626l-.134-.991c-1.762.24-3.668 1.463-5.186 2.889c-1.515 1.424-2.76 3.16-3.107 4.548z");
}

.yz9yob3rx {
  stop-color: var(--svg-color--7d6159, #7D6159);
  stop-opacity: 0;
}

.z_zoucbsi {
  stop-color: var(--svg-color--7f5056, #7F5056);
}

.z06a1xbjg {
  stop-color: var(--svg-color--895a5c, #895A5C);
}

.z2lq_sbqg {
  stop-color: var(--svg-color--8b6d5f, #8B6D5F);
}

.zrl62jbaz {
  d: path("M25.014 16.828c.506.759 2.301 1.622 3.405 1.86c.458 1.22 1.219 6.813-2.156 9.032c.785-1.374 1.335-6.449-1.25-10.892");
}

.zzirkubdu {
  stop-color: var(--svg-color--8a5d5b, #8A5D5B);
}

</style>
