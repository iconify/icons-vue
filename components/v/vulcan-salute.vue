<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iozyrQd)"><path class="n6iiumrsl"/><path fill="url(#iWwnLPb)" class="ghp_1jbdc"/><path fill="url(#iwkAGcb)" class="ghp_1jbdc"/></g><path fill="url(#i54ufhb)" class="t81k79ufj"/><path fill="url(#iXXNtVb)" class="t81k79ufj"/><g filter="url(#i0Mjars)"><rect transform="rotate(-22.578 4.808 8.777)" class="zfryazbyt"/></g><path fill="url(#inKXmtd)" class="h3wy5ftda"/><path fill="url(#iq3oKge)" class="h3wy5ftda"/><path fill="url(#iIlPndb)" class="h3wy5ftda"/><path fill="url(#i8K6HRd)" class="h3wy5ftda"/><g filter="url(#iLXlBXc)"><rect transform="rotate(-19.107 9.246 5.434)" class="c-eu1xlsr"/></g><path fill="url(#iKeKWUd)" class="lu7ex7a1h"/><path fill="url(#i6nGSet)" class="lu7ex7a1h"/><path fill="url(#ix7T8Cc)" class="lu7ex7a1h"/><path fill="url(#igpcWMc)" class="lu7ex7a1h"/><g filter="url(#iGHDfYh)"><rect fill="url(#iPATmde)" transform="rotate(16.763 18.943 3.74)" class="blse5abyj"/></g><path fill="url(#i8n8UWc)" class="eek_f87xu"/><path fill="url(#i5tlBlj)" class="eek_f87xu"/><path fill="url(#iViceBe)" class="eek_f87xu"/><g filter="url(#ix483Md)"><rect fill="url(#inAc1Hd)" transform="rotate(20.79 23.369 5.676)" class="t05_00zmy"/></g><path fill="url(#iBg2BWd)" class="ghp_1jbdc"/><path fill="url(#iOFKNGb)" class="ghp_1jbdc"/><path fill="url(#iNW8nNe)" class="ghp_1jbdc"/><path fill="url(#imuH8Qb)" class="ghp_1jbdc"/><path fill="url(#irr3u8b)" class="ghp_1jbdc"/><path fill="url(#iqe7DmV)" class="ghp_1jbdc"/><path fill="url(#iWUs11b)" class="ghp_1jbdc"/><g filter="url(#idWOjEq)"><path stroke="url(#iERx2dc)" class="dheubqcnm"/></g><defs><radialGradient id="iWwnLPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.76053 9.33077 -4.7965 -1.41906 21.622 24.016)" gradientUnits="userSpaceOnUse"><stop class="t0i4vjbzl"/><stop offset="1" class="ehmawyb_l"/></radialGradient><radialGradient id="iwkAGcb" cx="0" cy="0" r="1" gradientTransform="matrix(5.57964 -3.27694 6.45506 10.99104 6.955 26.734)" gradientUnits="userSpaceOnUse"><stop class="tmgfrsbmt"/><stop offset="1" class="bnszbnbmr"/></radialGradient><radialGradient id="iq3oKge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21117 7.64457 0 10.412 14.765)" gradientUnits="userSpaceOnUse"><stop class="y4_8unbts"/><stop offset="1" class="up3ckccta"/></radialGradient><radialGradient id="iIlPndb" cx="0" cy="0" r="1" gradientTransform="matrix(-.88994 .30388 -1.63403 -4.7854 13.346 9.49)" gradientUnits="userSpaceOnUse"><stop class="y9vaghv6h"/><stop offset="1" class="u_jhpwbct"/></radialGradient><radialGradient id="i8K6HRd" cx="0" cy="0" r="1" gradientTransform="matrix(.41951 -.13185 1.49361 4.7524 8.574 12.124)" gradientUnits="userSpaceOnUse"><stop class="nkcxa9bas"/><stop offset="1" class="p_h9ssb-r"/></radialGradient><radialGradient id="iViceBe" cx="0" cy="0" r="1" gradientTransform="rotate(-160.567 12.462 6.107)scale(.74532 1.9169)" gradientUnits="userSpaceOnUse"><stop class="wqq1s4dgw"/><stop offset="1" class="ge8858bzu"/></radialGradient><radialGradient id="iBg2BWd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27699 19.88296 -15.22175 -2.50875 16.564 10.482)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="ni2vaxx4p"/><stop offset="1" class="rmb7ona6l"/></radialGradient><radialGradient id="iOFKNGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.024 2.56503 -.76615 -.00717 13.692 10.159)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v_iu_kb4x"/><stop offset="1" class="efor37vxh"/></radialGradient><radialGradient id="iNW8nNe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50112 2.19034 -2.12493 -2.42643 29.103 13.589)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></radialGradient><radialGradient id="imuH8Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32576 3.22789 -3.80668 -1.56348 25.305 4.54)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></radialGradient><radialGradient id="irr3u8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38338 2.76677 -3.07497 -1.53748 20.463 3.04)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></radialGradient><radialGradient id="iqe7DmV" cx="0" cy="0" r="1" gradientTransform="matrix(-.2882 2.9397 -3.10526 -.30444 10.952 4.193)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></radialGradient><radialGradient id="iWUs11b" cx="0" cy="0" r="1" gradientTransform="matrix(.02881 2.30564 -1.70195 .02127 5.274 7.421)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></radialGradient><linearGradient id="i54ufhb" x1="9.034" x2="8.161" y1="11.67" y2="12.03" gradientUnits="userSpaceOnUse"><stop class="xfmd08bry"/><stop offset="1" class="qt1o4zluj"/></linearGradient><linearGradient id="iXXNtVb" x1="9.76" x2="8.412" y1="14.286" y2="13.006" gradientUnits="userSpaceOnUse"><stop class="y4_8unbts"/><stop offset="1" class="up3ckccta"/></linearGradient><linearGradient id="inKXmtd" x1="7.931" x2="10.412" y1="11.515" y2="10.599" gradientUnits="userSpaceOnUse"><stop class="ihgg2dqzp"/><stop offset="1" class="y1z8qccyu"/></linearGradient><linearGradient id="iKeKWUd" x1="13.935" x2="16.488" y1="8.165" y2="8.946" gradientUnits="userSpaceOnUse"><stop class="tb1nbcctq"/><stop offset="1" class="ztiolh4qs"/></linearGradient><linearGradient id="i6nGSet" x1="19.867" x2="18.59" y1="10.355" y2="9.987" gradientUnits="userSpaceOnUse"><stop class="bswvgtbwc"/><stop offset="1" class="zupnabc8g"/></linearGradient><linearGradient id="ix7T8Cc" x1="19.2" x2="18.859" y1="10.333" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="nkcxa9bas"/><stop offset="1" class="p_h9ssb-r"/></linearGradient><linearGradient id="igpcWMc" x1="17.299" x2="15.498" y1="14.953" y2="11.485" gradientUnits="userSpaceOnUse"><stop class="y4_8unbts"/><stop offset="1" class="up3ckccta"/></linearGradient><linearGradient id="iPATmde" x1="19.922" x2="20.102" y1="2.943" y2="15.949" gradientUnits="userSpaceOnUse"><stop class="cx4wjibom"/><stop offset="1" class="v4aeccbfm"/></linearGradient><linearGradient id="i8n8UWc" x1="18.48" x2="21.581" y1="10.415" y2="11.41" gradientUnits="userSpaceOnUse"><stop class="tb1nbcctq"/><stop offset="1" class="ztiolh4qs"/></linearGradient><linearGradient id="i5tlBlj" x1="19.224" x2="20.499" y1="16.331" y2="13.922" gradientUnits="userSpaceOnUse"><stop class="y4_8unbts"/><stop offset="1" class="up3ckccta"/></linearGradient><linearGradient id="inAc1Hd" x1="24.41" x2="24.58" y1="4.879" y2="17.885" gradientUnits="userSpaceOnUse"><stop class="cx4wjibom"/><stop offset="1" class="v4aeccbfm"/></linearGradient><linearGradient id="iERx2dc" x1="20.125" x2="21.681" y1="17.808" y2="14.465" gradientUnits="userSpaceOnUse"><stop class="fpxa8cbvp"/><stop offset=".632" class="d4_7lfbzy"/><stop offset="1" class="fbgwhlb-y"/></linearGradient><filter id="iozyrQd" width="27.027" height="28.645" x="2.826" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.537255 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1601"/></filter><filter id="i0Mjars" width="6.832" height="10.115" x="3.538" y="6.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1601" stdDeviation=".75"/></filter><filter id="iLXlBXc" width="6.91" height="11.467" x="7.95" y="3.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1601" stdDeviation=".75"/></filter><filter id="iGHDfYh" width="7.078" height="13.072" x="14.612" y="2.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1601" stdDeviation=".75"/></filter><filter id="ix483Md" width="7.735" height="12.875" x="18.389" y="4.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1601" stdDeviation=".75"/></filter><filter id="idWOjEq" width="4.132" height="6.62" x="18.848" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1601" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:vulcan-salute" /></template>
<style>
.blse5abyj {
  width: 1.494px;
  height: 10.452px;
  x: 18.943px;
  y: 3.74px;
  rx: 0.747px;
}

.bnszbnbmr {
  stop-color: var(--svg-color--f0a028, #F0A028);
  stop-opacity: 0;
}

.bswvgtbwc {
  stop-color: var(--svg-color--c67700, #C67700);
}

.c-eu1xlsr {
  width: 1.494px;
  height: 8.873px;
  x: 9.246px;
  y: 5.434px;
  fill: var(--svg-color--ffd93d, #FFD93D);
  rx: 0.747px;
}

.cx4wjibom {
  stop-color: var(--svg-color--ffd93d, #FFD93D);
}

.d4_7lfbzy {
  stop-color: var(--svg-color--ffd842, #FFD842);
  stop-opacity: 0.368;
}

.dheubqcnm {
  stroke-linecap: round;
  d: path("m20.348 17.364l1.131-3.62");
}

.eek_f87xu {
  d: path("m20.383 6.554l-2.85 8.68c.46.613 1.787 1.854 3.799 1.939c0-.036.3-.584.787-1.448l3.146-8.222a2.457 2.457 0 0 0-1.462-3.18c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.efor37vxh {
  stop-color: var(--svg-color--c89031, #C89031);
  stop-opacity: 0;
}

.ehmawyb_l {
  stop-color: var(--svg-color--ffcd46, #FFCD46);
  stop-opacity: 0;
}

.fbgwhlb-y {
  stop-color: var(--svg-color--ffd842, #FFD842);
  stop-opacity: 0;
}

.fgz6lbb_q {
  stop-color: var(--svg-color--ffe948, #FFE948);
}

.fpxa8cbvp {
  stop-color: var(--svg-color--ffd842, #FFD842);
}

.ft5dv1b6b {
  fill: none;
}

.ge8858bzu {
  stop-color: var(--svg-color--b47525, #B47525);
  stop-opacity: 0;
}

.ghp_1jbdc {
  d: path("M20.815 5.19a2.45 2.45 0 0 0-1.588-3.072a2.43 2.43 0 0 0-3.062 1.56c-.65 2.013-1.61 5.042-2.414 7.812c-.041.142-.241.146-.287.006c-.6-1.825-1.558-4.734-1.857-5.613c-.445-1.313-1.886-1.941-3.165-1.485A2.43 2.43 0 0 0 6.97 7.5l.368 1.034a2.45 2.45 0 0 0-4.37 2.143l.68 1.903c.235.697.904 2.518 1.147 4.87l.065.644c.245 2.454.52 5.22 1.954 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.476-.758c1.36-.584 2.62-1.48 3.6-2.801c1.16-1.473 1.546-2.167 2.138-3.23l.33-.59c.577-1.02 1.764-2.612 2.446-3.496l2.284-2.58c.953-1.03 1.042-2.55-.104-3.61c-1.03-.952-2.735-.807-3.862.438l-2.284 2.457l3.147-8.222a2.457 2.457 0 0 0-1.462-3.18c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.h3wy5ftda {
  d: path("M13.464 11.496a.15.15 0 0 0 .037.06l.495 1.982c-1.612 1.435-3.435 1.475-4.143 1.386l-.238-.598l.003-.004L7.32 8.506l.018.029L6.97 7.5a2.43 2.43 0 0 1 1.472-3.104c1.279-.455 2.72.173 3.165 1.486c.299.879 1.257 3.788 1.857 5.613");
}

.ihgg2dqzp {
  stop-color: var(--svg-color--e5910c, #E5910C);
}

.lu7ex7a1h {
  d: path("M13.668 11.586c.083 2.689 2.762 3.826 3.94 3.482l2.865-8.797l.342-1.081a2.45 2.45 0 0 0-1.588-3.072a2.43 2.43 0 0 0-3.062 1.56c-.65 2.013-1.61 5.042-2.414 7.812a.15.15 0 0 1-.083.096");
}

.n6iiumrsl {
  fill: var(--svg-color--ffc23e, #FFC23E);
  d: path("M20.815 5.19a2.45 2.45 0 0 0-1.588-3.072a2.43 2.43 0 0 0-3.062 1.56c-.65 2.013-1.61 5.042-2.414 7.812c-.041.142-.241.146-.287.006c-.6-1.825-1.558-4.734-1.857-5.613c-.445-1.313-1.886-1.941-3.165-1.485A2.43 2.43 0 0 0 6.97 7.5l.368 1.034a2.45 2.45 0 0 0-4.37 2.143l.68 1.903c.235.697.904 2.518 1.147 4.87l.065.644c.245 2.454.52 5.22 1.954 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.476-.758c1.36-.584 2.62-1.48 3.6-2.801c1.16-1.473 1.546-2.167 2.138-3.23l.33-.59c.577-1.02 1.764-2.612 2.446-3.496l2.284-2.58c.953-1.03 1.042-2.55-.104-3.61c-1.03-.952-2.735-.807-3.862.438l-2.284 2.457l3.147-8.222a2.457 2.457 0 0 0-1.462-3.18c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.ni2vaxx4p {
  stop-color: var(--svg-color--f67b7a, #F67B7A);
  stop-opacity: 0;
}

.nkcxa9bas {
  stop-color: var(--svg-color--803800, #803800);
}

.p_h9ssb-r {
  stop-color: var(--svg-color--803800, #803800);
  stop-opacity: 0;
}

.qt1o4zluj {
  stop-color: var(--svg-color--c97c00, #C97C00);
  stop-opacity: 0;
}

.rmb7ona6l {
  stop-color: var(--svg-color--f67b7a, #F67B7A);
}

.t05_00zmy {
  width: 1.589px;
  height: 10.452px;
  x: 23.369px;
  y: 5.676px;
  rx: 0.794px;
}

.t0i4vjbzl {
  stop-color: var(--svg-color--ffcd46, #FFCD46);
}

.t81k79ufj {
  d: path("M4.533 15.728a4.99 4.99 0 0 0 5.085-1.405L7.32 8.506a2.45 2.45 0 0 0-4.351 2.172l.678 1.903l.058.169c.196.57.557 1.622.828 2.978");
}

.tb1nbcctq {
  stop-color: var(--svg-color--dd9627, #DD9627);
}

.tmgfrsbmt {
  stop-color: var(--svg-color--f0a028, #F0A028);
}

.u_jhpwbct {
  stop-color: var(--svg-color--c5923e, #C5923E);
  stop-opacity: 0;
}

.up3ckccta {
  stop-color: var(--svg-color--ffc23e, #FFC23E);
  stop-opacity: 0;
}

.v_iu_kb4x {
  stop-color: var(--svg-color--c89031, #C89031);
}

.v4aeccbfm {
  stop-color: var(--svg-color--ffd93d, #FFD93D);
  stop-opacity: 0;
}

.wqq1s4dgw {
  stop-color: var(--svg-color--b47525, #B47525);
}

.x9idaudaq {
  stop-color: var(--svg-color--ffe948, #FFE948);
  stop-opacity: 0;
}

.xfmd08bry {
  stop-color: var(--svg-color--c97c00, #C97C00);
}

.y1z8qccyu {
  stop-color: var(--svg-color--e5910c, #E5910C);
  stop-opacity: 0;
}

.y4_8unbts {
  stop-color: var(--svg-color--ffc23e, #FFC23E);
}

.y9vaghv6h {
  stop-color: var(--svg-color--c5923e, #C5923E);
}

.zfryazbyt {
  width: 1.494px;
  height: 7.581px;
  x: 4.808px;
  y: 8.777px;
  fill: var(--svg-color--ffd93d, #FFD93D);
  rx: 0.747px;
}

.ztiolh4qs {
  stop-color: var(--svg-color--dd9627, #DD9627);
  stop-opacity: 0;
}

.zupnabc8g {
  stop-color: var(--svg-color--c67700, #C67700);
  stop-opacity: 0;
}

</style>
