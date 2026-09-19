<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i88NTvd)" transform="rotate(45 10.492 2.773)" class="ny9osubsz"/><g filter="url(#iqnAguc)"><path class="bze26mh4u"/><path fill="url(#iAQ6uye)" class="i6ozihb-g"/></g><g filter="url(#iyIRXCb)"><path class="ub2v97wof"/><path fill="url(#iJyC9id)" class="rmvav29wl"/></g><g filter="url(#iAAYZNa)"><path class="gdeb-z4yu"/><path fill="url(#iCvX8Sr)" class="khzet3bde"/></g><g filter="url(#ibNuvwX)"><path class="sierv-tck"/><path fill="url(#i01CJXP)" class="w9-lsccye"/></g><g filter="url(#i6KlqWd)"><path class="x172beb-o"/><path fill="url(#ilndZHc)" class="y84dp6_6z"/></g><g filter="url(#ifrAT0U)"><path fill="url(#ieuheWc)" class="j8-myibuy"/></g><g filter="url(#iI0tSzd)"><path stroke="url(#imtOQjc)" class="fuyd7qzky"/></g><defs><filter id="iqnAguc" width="6.66" height="6.06" x="5.032" y="2.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.74902 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26298"/></filter><filter id="iyIRXCb" width="6.66" height="6.06" x="6.499" y="3.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.74902 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26298"/></filter><filter id="iAAYZNa" width="6.66" height="6.06" x="7.888" y="4.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.74902 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26298"/></filter><filter id="ibNuvwX" width="6.66" height="6.06" x="9.297" y="6.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.74902 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26298"/></filter><filter id="i6KlqWd" width="6.66" height="6.06" x="10.777" y="7.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.74902 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26298"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.729412 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26298" result="effect2_innerShadow_18_26298"/></filter><filter id="ifrAT0U" width="26.548" height="25.296" x="2.895" y="4.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.109804 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26298"/></filter><filter id="iI0tSzd" width="24.113" height="23.35" x="5.062" y="5.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26298" stdDeviation=".375"/></filter><radialGradient id="iAQ6uye" cx="0" cy="0" r="1" gradientTransform="rotate(138.827 5.03 3.458)scale(.80696 1.0457)" gradientUnits="userSpaceOnUse"><stop class="up3080b4m"/><stop offset="1" class="w1xkpxbjw"/></radialGradient><radialGradient id="iJyC9id" cx="0" cy="0" r="1" gradientTransform="rotate(138.827 5.492 4.456)scale(.80696 1.0457)" gradientUnits="userSpaceOnUse"><stop class="up3080b4m"/><stop offset="1" class="w1xkpxbjw"/></radialGradient><radialGradient id="iCvX8Sr" cx="0" cy="0" r="1" gradientTransform="rotate(138.827 5.924 5.417)scale(.80696 1.0457)" gradientUnits="userSpaceOnUse"><stop class="up3080b4m"/><stop offset="1" class="w1xkpxbjw"/></radialGradient><radialGradient id="i01CJXP" cx="0" cy="0" r="1" gradientTransform="rotate(138.827 6.363 6.387)scale(.80696 1.0457)" gradientUnits="userSpaceOnUse"><stop class="up3080b4m"/><stop offset="1" class="w1xkpxbjw"/></radialGradient><radialGradient id="ilndZHc" cx="0" cy="0" r="1" gradientTransform="rotate(138.827 6.845 7.35)scale(.80696 1.0457)" gradientUnits="userSpaceOnUse"><stop class="up3080b4m"/><stop offset="1" class="w1xkpxbjw"/></radialGradient><linearGradient id="i88NTvd" x1="14.387" x2="14.387" y1="2.773" y2="8.149" gradientUnits="userSpaceOnUse"><stop class="vn81g7b7s"/><stop offset=".479" class="a0t0lobzv"/></linearGradient><linearGradient id="ieuheWc" x1="15.969" x2="19.578" y1="5.033" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="hpq0ghbdu"/><stop offset="1" class="doh71gb9d"/></linearGradient><linearGradient id="imtOQjc" x1="28.987" x2="-7.297" y1="26.781" y2="-9.375" gradientUnits="userSpaceOnUse"><stop class="q6m9chopz"/><stop offset="1" class="vynjf-lqn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:toothbrush" /></template>
<style>
.a0t0lobzv {
  stop-color: var(--svg-color--d8c6d5, #D8C6D5);
}

.bze26mh4u {
  fill: var(--svg-color--e2d1e3, #E2D1E3);
  d: path("M9.499 2.326a.933.933 0 1 1 1.32 1.32L6.624 7.838a.933.933 0 1 1-1.32-1.32z");
}

.doh71gb9d {
  stop-color: var(--svg-color--ec2d97, #EC2D97);
}

.ft5dv1b6b {
  fill: none;
}

.fuyd7qzky {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m6.112 6.313l7.009 7.037a6 6 0 0 0 1.383 1.036l3.181 1.732c.657.357 1.26.805 1.792 1.33l8.01 7.896c.333.416.9 1.444.5 2.218");
}

.gdeb-z4yu {
  fill: var(--svg-color--e2d1e3, #E2D1E3);
  d: path("M12.356 5.17a.933.933 0 0 1 1.32 1.32L9.48 10.682a.933.933 0 1 1-1.32-1.32z");
}

.hpq0ghbdu {
  stop-color: var(--svg-color--ff2539, #FF2539);
}

.i6ozihb-g {
  d: path("M9.499 2.326a.933.933 0 1 1 1.32 1.32L6.624 7.838a.933.933 0 1 1-1.32-1.32z");
}

.j8-myibuy {
  d: path("M3.526 5.664a2.155 2.155 0 0 0 0 3.048l20.317 20.324a3.046 3.046 0 1 0 4.297-4.318l-8.21-8.132a6 6 0 0 0-1.439-1.052l-2.277-1.193c-1.502-.787-2.407-1.472-4.008-3.038L6.573 5.664a2.155 2.155 0 0 0-3.047 0");
}

.khzet3bde {
  d: path("M12.356 5.17a.933.933 0 0 1 1.32 1.32L9.48 10.682a.933.933 0 1 1-1.32-1.32z");
}

.ny9osubsz {
  d: path("M10.492 2.773h7.789v5.376h-7.789z");
}

.q6m9chopz {
  stop-color: var(--svg-color--f95eaa, #F95EAA);
}

.rmvav29wl {
  d: path("M10.966 3.77a.933.933 0 1 1 1.32 1.32L8.09 9.284a.933.933 0 0 1-1.32-1.32z");
}

.sierv-tck {
  fill: var(--svg-color--e2d1e3, #E2D1E3);
  d: path("M13.765 6.58a.933.933 0 1 1 1.32 1.32l-4.195 4.194a.933.933 0 0 1-1.32-1.32z");
}

.ub2v97wof {
  fill: var(--svg-color--e2d1e3, #E2D1E3);
  d: path("M10.966 3.77a.933.933 0 1 1 1.32 1.32L8.09 9.284a.933.933 0 0 1-1.32-1.32z");
}

.up3080b4m {
  stop-color: var(--svg-color--f2edfb, #F2EDFB);
}

.vn81g7b7s {
  stop-color: var(--svg-color--ece6f5, #ECE6F5);
}

.vynjf-lqn {
  stop-color: var(--svg-color--f95eaa, #F95EAA);
  stop-opacity: 0;
}

.w1xkpxbjw {
  stop-color: var(--svg-color--f2edfb, #F2EDFB);
  stop-opacity: 0;
}

.w9-lsccye {
  d: path("M13.765 6.58a.933.933 0 1 1 1.32 1.32l-4.195 4.194a.933.933 0 0 1-1.32-1.32z");
}

.x172beb-o {
  fill: var(--svg-color--e2d1e3, #E2D1E3);
  d: path("M15.244 7.952a.933.933 0 0 1 1.32 1.32l-4.194 4.193a.933.933 0 1 1-1.32-1.32z");
}

.y84dp6_6z {
  d: path("M15.244 7.952a.933.933 0 0 1 1.32 1.32l-4.194 4.193a.933.933 0 1 1-1.32-1.32z");
}

</style>
