<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iD62EHb)"><path fill="url(#imXP1yb)" class="fabd9pbqf"/><path fill="url(#iMbc7fe)" class="fabd9pbqf"/></g><g filter="url(#ikYsBJd)"><path fill="url(#ikvLGOe)" class="h8pj8ubhk"/><path fill="url(#i6oXN5c)" class="h8pj8ubhk"/></g><g filter="url(#iITynPc)" class="gqza14sjk"><path class="xn4smvl0w"/><path stroke="url(#iGzRGqb)" class="odzqra34h"/></g><path stroke="url(#iZfN6cb)" class="njkj0vb8r"/><g filter="url(#iDO59Vd)"><path stroke="url(#itkUUmd)" class="xvbu_d0_o"/></g><g filter="url(#i04oQod)"><path fill="url(#iLIKYDi)" class="yg6kjlbdq"/></g><path fill="url(#iCwjYJC)" class="wk1w_fb6v"/><path fill="url(#iUPUUic)" class="wk1w_fb6v"/><path fill="url(#i2owSMc)" class="wk1w_fb6v"/><g filter="url(#iLu8WYb)"><path fill="url(#iv55s2d)" clip-rule="evenodd" class="iygc7qbsw"/></g><g filter="url(#ibO0ife)" class="bbpfkd-8o"><path stroke="url(#iiki5Ce)" class="l2cw1wbji"/><path stroke="url(#i6j6yte)" class="l2cw1wbji"/></g><defs><linearGradient id="ikvLGOe" x1="14.165" x2="16.428" y1="18.521" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="b2cgg2bbf"/><stop offset="1" class="aj_vy6blb"/></linearGradient><linearGradient id="i6oXN5c" x1="19.968" x2="18.985" y1="29.09" y2="29.362" gradientUnits="userSpaceOnUse"><stop offset=".211" class="mgch1cbbg"/><stop offset="1" class="pa7vlrirt"/></linearGradient><linearGradient id="iCwjYJC" x1="16.357" x2="16.357" y1="23.638" y2="24.156" gradientUnits="userSpaceOnUse"><stop class="y38ovebgg"/><stop offset="1" class="swyep4p0t"/></linearGradient><linearGradient id="iUPUUic" x1="19.053" x2="18.363" y1="25.741" y2="25.933" gradientUnits="userSpaceOnUse"><stop offset=".049" class="wsqx31her"/><stop offset="1" class="m-mlopbsp"/></linearGradient><linearGradient id="i2owSMc" x1="14.074" x2="14.934" y1="25.695" y2="25.446" gradientUnits="userSpaceOnUse"><stop class="d5r9gdykk"/><stop offset="1" class="sqjw9lbgb"/></linearGradient><linearGradient id="iv55s2d" x1="14.186" x2="19.186" y1="27.406" y2="23.281" gradientUnits="userSpaceOnUse"><stop class="s3p8bo6dn"/><stop offset="1" class="l33d-9blo"/></linearGradient><linearGradient id="iiki5Ce" x1="20.001" x2="16.845" y1="24.344" y2="26.469" gradientUnits="userSpaceOnUse"><stop offset=".182" class="be1ko7b3d"/><stop offset="1" class="q1att5_7v"/></linearGradient><linearGradient id="i6j6yte" x1="13.345" x2="17.811" y1="26.406" y2="25.344" gradientUnits="userSpaceOnUse"><stop class="be1ko7b3d"/><stop offset="1" class="q1att5_7v"/></linearGradient><filter id="iD62EHb" width="28.094" height="19.48" x="2.42" y="1.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.486275 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17570"/></filter><filter id="ikYsBJd" width="8.436" height="13.216" x="12.032" y="16.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.286275 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17570"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.266667 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17570" result="effect2_innerShadow_18_17570"/></filter><filter id="iITynPc" width="27.969" height="13.102" x="2.357" y="10.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.380392 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17570"/></filter><filter id="iDO59Vd" width="27.219" height="11.353" x="2.732" y="11.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17570" stdDeviation=".375"/></filter><filter id="i04oQod" width="14.909" height="13.068" x="12.889" y="3.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17570" stdDeviation="1"/></filter><filter id="iLu8WYb" width="7.449" height="4.456" x="12.566" y="22.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.517647 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17570"/></filter><filter id="ibO0ife" width="7.359" height="4.037" x="12.677" y="22.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17570" stdDeviation=".15"/></filter><radialGradient id="imXP1yb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71593 14.03239 -25.93951 5.02052 12.354 3.13)" gradientUnits="userSpaceOnUse"><stop class="ruhab4bvd"/><stop offset="1" class="nhif2m_0x"/></radialGradient><radialGradient id="iMbc7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.49998 8.75 -10.04736 -5.16719 18.686 1.188)" gradientUnits="userSpaceOnUse"><stop class="dt08rbb7v"/><stop offset="1" class="w5pc-73rf"/></radialGradient><radialGradient id="iGzRGqb" cx="0" cy="0" r="1" gradientTransform="matrix(.76952 2.12749 -8.53466 3.08701 6.107 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="jqfvbj6qs"/><stop offset="1" class="scoa3bcrc"/></radialGradient><radialGradient id="iZfN6cb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17691 -3.34967 18.21303 -6.39917 13.53 21.056)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="oggk5krgn"/><stop offset="1" class="p1wpqjb8r"/></radialGradient><radialGradient id="itkUUmd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.06253 5.25004 -1.16103 -2.44645 21.623 14.375)" gradientUnits="userSpaceOnUse"><stop class="trjny3bvi"/><stop offset="1" class="wl8x_bc6b"/></radialGradient><radialGradient id="iLIKYDi" cx="0" cy="0" r="1" gradientTransform="rotate(-165.28 13.265 3.836)scale(11.0452 13.2875)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="zwjasxdsb"/><stop offset="1" class="fvs5yzb8z"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:military-helmet" /></template>
<style>
.aj_vy6blb {
  stop-color: var(--svg-color--9e6168, #9E6168);
}

.b2cgg2bbf {
  stop-color: var(--svg-color--77444f, #77444F);
}

.bbpfkd-8o {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
}

.be1ko7b3d {
  stop-color: var(--svg-color--cfc3dd, #CFC3DD);
}

.d5r9gdykk {
  stop-color: var(--svg-color--553f40, #553F40);
}

.dt08rbb7v {
  stop-color: var(--svg-color--62a05f, #62A05F);
}

.fabd9pbqf {
  d: path("M18.248 16.063c3.923-2.022 7.35-2.965 9.854-3.345q-.074-.538-.195-1.066l1.107-.464c-1.097-.33-1.609-1.322-1.868-1.826l-.001-.002a12.35 12.35 0 0 0-5.647-5.98C15.408.24 7.926 2.63 4.785 8.72q-.345.668-.6 1.354c-.224.47-.83 2.163-1.015 3.911c-.077.72-.083 1.452-.09 2.204c-.014 1.553-.029 3.19-.66 4.968c.627.073 1.726.104 2.948-.047q.12.186.246.369c3.594-.995 7.306-2.67 12.634-5.416");
}

.ft5dv1b6b {
  fill: none;
}

.fvs5yzb8z {
  stop-color: var(--svg-color--639679, #639679);
  stop-opacity: 0;
}

.gqza14sjk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--3px, 3px);
}

.h8pj8ubhk {
  d: path("m12.032 18.597l4.554-1.317l3.353 11.76a.75.75 0 0 1-.736.956l-3.19-.063a1 1 0 0 1-.94-.725z");
}

.iygc7qbsw {
  fill-rule: evenodd;
  d: path("M12.62 24.299a1.1 1.1 0 0 1 1.047-1.44h4.69a1.1 1.1 0 0 1 1.059.8l.556 1.956a1.1 1.1 0 0 1-1.058 1.4h-4.613a1.1 1.1 0 0 1-1.046-.76zm1.327-.44c-.28 0-.3.313-.28.383l.437 1.372c.013.042.129.402.511.402h4.012c.067 0 .414-.047.288-.426l-.429-1.48c-.012-.044-.097-.25-.418-.25z");
}

.jqfvbj6qs {
  stop-color: var(--svg-color--617364, #617364);
}

.l2cw1wbji {
  d: path("M13.215 24.342c-.154-.432.194-.923.761-.923h4.256c.369 0 .676.222.769.52l.505 1.618c.134.428-.215.9-.769.9h-4.185c-.358 0-.66-.21-.761-.497z");
}

.l33d-9blo {
  stop-color: var(--svg-color--a182bc, #A182BC);
}

.m-mlopbsp {
  stop-color: var(--svg-color--713f3e, #713F3E);
  stop-opacity: 0;
}

.mgch1cbbg {
  stop-color: var(--svg-color--b7827b, #B7827B);
}

.nhif2m_0x {
  stop-color: var(--svg-color--35664d, #35664D);
}

.njkj0vb8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M3.857 21.61c1.141 0 3.247-.528 4.579-1.079c4.343-1.797 16.875-8.297 20.39-8.015");
}

.odzqra34h {
  d: path("M3.857 21.61c1.141 0 3.247-.528 4.579-1.079c4.343-1.797 16.875-8.297 20.39-8.015");
}

.oggk5krgn {
  stop-color: var(--svg-color--384d6d, #384D6D);
}

.p1wpqjb8r {
  stop-color: var(--svg-color--384d6d, #384D6D);
  stop-opacity: 0;
}

.pa7vlrirt {
  stop-color: var(--svg-color--9c686b, #9C686B);
  stop-opacity: 0;
}

.q1att5_7v {
  stop-color: var(--svg-color--cfc3dd, #CFC3DD);
  stop-opacity: 0;
}

.ruhab4bvd {
  stop-color: var(--svg-color--4e904b, #4E904B);
}

.s3p8bo6dn {
  stop-color: var(--svg-color--a175c4, #A175C4);
}

.scoa3bcrc {
  stop-color: var(--svg-color--617364, #617364);
  stop-opacity: 0;
}

.sqjw9lbgb {
  stop-color: var(--svg-color--754543, #754543);
  stop-opacity: 0;
}

.swyep4p0t {
  stop-color: var(--svg-color--83495b, #83495B);
  stop-opacity: 0;
}

.trjny3bvi {
  stop-color: var(--svg-color--659384, #659384);
}

.w5pc-73rf {
  stop-color: var(--svg-color--62a05f, #62A05F);
  stop-opacity: 0;
}

.wk1w_fb6v {
  d: path("m14.319 26.578l-.843-2.94h4.922l.839 2.94z");
}

.wl8x_bc6b {
  stop-color: var(--svg-color--659384, #659384);
  stop-opacity: 0;
}

.wsqx31her {
  stop-color: var(--svg-color--4c2327, #4C2327);
}

.xn4smvl0w {
  stroke: var(--svg-color--31715a, #31715A);
  d: path("M3.857 21.61c1.141 0 3.247-.528 4.579-1.079c4.343-1.797 16.875-8.297 20.39-8.015");
}

.xvbu_d0_o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M3.857 21.61c1.141 0 3.247-.528 4.579-1.079c4.343-1.797 16.875-8.297 20.39-8.015");
}

.y38ovebgg {
  stop-color: var(--svg-color--83495b, #83495B);
}

.yg6kjlbdq {
  d: path("M19.642 12.998c-1.775.688-3.908 1.253-4.753 1.449c0-6.473 6.156-10.411 8.102-8.646c1.558 1.412 2.52 4.029 2.807 5.16c-1.901.317-3.938 1.177-6.156 2.037");
}

.zwjasxdsb {
  stop-color: var(--svg-color--639679, #639679);
}

</style>
