<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="m9ljo8d4z"/><path stroke="url(#igTBFje)" class="r04vkbcgp"/><path stroke="url(#iVclBjs)" class="r04vkbcgp"/><g filter="url(#ittUfzc)"><path clip-rule="evenodd" class="t7qm6w8_t"/></g><path fill="url(#izFWqve)" class="ckw76qbwb"/><path fill="url(#i3RUl1d)" class="ckw76qbwb"/><path fill="url(#idCbIUb)" class="sbdokfbcb"/><path fill="url(#ixMfQvB)" class="sbdokfbcb"/><g filter="url(#iCVAMOc)"><path stroke="url(#iwdhoEc)" class="m5fyzb_tu"/></g><g filter="url(#i0qlPge)"><circle stroke="url(#ihtywIb)" class="y2zrw-j-v"/></g><g filter="url(#ipIckob)"><path fill="url(#iTpXgQb)" class="esmkn6ppb"/><path fill="url(#iOl0wVc)" class="esmkn6ppb"/></g><path fill="url(#iOKIeMc)" class="esmkn6ppb"/><defs><linearGradient id="igTBFje" x1="16.625" x2="19.281" y1="19.625" y2="22.438" gradientUnits="userSpaceOnUse"><stop offset=".181" class="yb_9u_b1r"/><stop offset="1" class="pgjciwbeu"/></linearGradient><linearGradient id="izFWqve" x1="6.094" x2="9.886" y1="20.503" y2="20.852" gradientUnits="userSpaceOnUse"><stop offset=".152" class="rvj9qpbua"/><stop offset="1" class="joyaipeyk"/></linearGradient><linearGradient id="idCbIUb" x1="15.688" x2="13.922" y1="11" y2="12.766" gradientUnits="userSpaceOnUse"><stop class="y0cbcvb2f"/><stop offset="1" class="cc_9tc7lh"/></linearGradient><linearGradient id="ixMfQvB" x1="11.75" x2="10.219" y1="16.5" y2="14.969" gradientUnits="userSpaceOnUse"><stop offset=".398" class="n0x48zbap"/><stop offset="1" class="thaw0cv6c"/></linearGradient><linearGradient id="iwdhoEc" x1="3.688" x2="9.475" y1="15.75" y2="17.192" gradientUnits="userSpaceOnUse"><stop class="s-kpyfbkz"/><stop offset="1" class="zj2tbybeq"/></linearGradient><linearGradient id="ihtywIb" x1="6.563" x2="9.303" y1="25.875" y2="16.875" gradientUnits="userSpaceOnUse"><stop class="s-kpyfbkz"/><stop offset="1" class="zj2tbybeq"/></linearGradient><linearGradient id="iTpXgQb" x1="20.934" x2="16.63" y1="10.03" y2="5.037" gradientUnits="userSpaceOnUse"><stop class="o27rcpbsd"/><stop offset="1" class="jo5zsvbfj"/></linearGradient><linearGradient id="iOl0wVc" x1="12.563" x2="15.344" y1="7.188" y2="9.344" gradientUnits="userSpaceOnUse"><stop offset=".127" class="pl-qj2bwi"/><stop offset="1" class="ls4k_hoak"/></linearGradient><filter id="ittUfzc" width="14.883" height="22.188" x="2.08" y="7.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.631373 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26095"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26095" result="effect2_innerShadow_18_26095"/></filter><filter id="iCVAMOc" width="10.952" height="10.881" x="4.619" y="8.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26095" stdDeviation=".25"/></filter><filter id="i0qlPge" width="12.833" height="12.833" x="2.886" y="16.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26095" stdDeviation=".25"/></filter><filter id="ipIckob" width="17.934" height="18.204" x="11.967" y="1.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.635294 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26095"/></filter><radialGradient id="iVclBjs" cx="0" cy="0" r="1" gradientTransform="matrix(-3.317 3.42898 -2.1829 -2.1116 22.66 18.5)" gradientUnits="userSpaceOnUse"><stop class="zyy6vkbhq"/><stop offset="1" class="b2eo_ibcr"/></radialGradient><radialGradient id="i3RUl1d" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 -4.8125 7.32972 7.28214 10.688 22.219)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="w14w13bzo"/><stop offset=".955" class="bv7mydbul"/></radialGradient><radialGradient id="iOKIeMc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.45099 4.85188 -5.92359 -10.31768 31.304 6.189)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="y_-s2_b4a"/><stop offset="1" class="efdvjk2xy"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:safety-pin" /></template>
<style>
.b2eo_ibcr {
  stop-color: var(--svg-color--ab93c0, #AB93C0);
  stop-opacity: 0;
}

.bv7mydbul {
  stop-color: var(--svg-color--a8a5b0, #A8A5B0);
}

.cc_9tc7lh {
  stop-color: var(--svg-color--b4a0c9, #B4A0C9);
  stop-opacity: 0;
}

.ckw76qbwb {
  d: path("m13.852 12.986l-.013-.013l-2.953 2.954l-4.02 4.02a3.716 3.716 0 0 1 4.791 5.68l2.407 2.406a7.12 7.12 0 0 0-3.178-12.106z");
}

.efdvjk2xy {
  stop-color: var(--svg-color--e0dfe4, #E0DFE4);
  stop-opacity: 0;
}

.esmkn6ppb {
  d: path("M16.12 4.407a8 8 0 0 1 11.314 0l.124.124a8 8 0 0 1 .198 11.108l-.002.025c-1.422 1.422-2.837 2.873-4.242 4.28a.25.25 0 0 1-.353.001l-3.53-3.515l.008-.008l-.48-.48a3.697 3.697 0 1 1 5.234-5.221l.138.122c.09.08.23.06.272-.052c.267-.73-.166-2.027-.883-2.744a2.895 2.895 0 0 0-4.094 0L17.48 10.39a2.75 2.75 0 0 1-3.89 0l-1.55-1.55a.25.25 0 0 1 0-.354z");
}

.ft5dv1b6b {
  fill: none;
}

.jo5zsvbfj {
  stop-color: var(--svg-color--b5afbf, #B5AFBF);
}

.joyaipeyk {
  stop-color: var(--svg-color--b9a5cd, #B9A5CD);
  stop-opacity: 0;
}

.ls4k_hoak {
  stop-color: var(--svg-color--b0abb8, #B0ABB8);
  stop-opacity: 0;
}

.m5fyzb_tu {
  d: path("M14.719 9.402L5.47 18.574");
}

.m9ljo8d4z {
  stroke: var(--svg-color--dacaec, #DACAEC);
  stroke-width: var(--svg-stroke-width--3-4px, 3.4px);
  d: path("m22.66 17.098l-9.737 9.661");
}

.n0x48zbap {
  stop-color: var(--svg-color--c5b5d8, #C5B5D8);
}

.o27rcpbsd {
  stop-color: var(--svg-color--cec2dd, #CEC2DD);
}

.pgjciwbeu {
  stop-color: var(--svg-color--c7bbd6, #C7BBD6);
  stop-opacity: 0;
}

.pl-qj2bwi {
  stop-color: var(--svg-color--9c9b9f, #9C9B9F);
}

.r04vkbcgp {
  stroke-width: var(--svg-stroke-width--3-4px, 3.4px);
  d: path("m22.66 17.098l-9.737 9.661");
}

.rvj9qpbua {
  stop-color: var(--svg-color--b9a5cd, #B9A5CD);
}

.s-kpyfbkz {
  stop-color: var(--svg-color--dfd4ec, #DFD4EC);
}

.sbdokfbcb {
  d: path("M16 10.813L13.627 8.42L4.38 17.59l.007.007a7.1 7.1 0 0 0-2.073 3.433l3.5-2.125l.49 1.604a3.7 3.7 0 0 1 .563-.563z");
}

.t7qm6w8_t {
  fill: var(--svg-color--d0c5dd, #D0C5DD);
  fill-rule: evenodd;
  d: path("M13.627 8.42L4.38 17.59l.007.007a7.116 7.116 0 1 0 6.5-1.671l5.135-5.093zM5.48 22.84a3.716 3.716 0 1 1 7.433 0a3.716 3.716 0 0 1-7.433 0");
}

.thaw0cv6c {
  stop-color: var(--svg-color--c5b5d8, #C5B5D8);
  stop-opacity: 0;
}

.w14w13bzo {
  stop-color: var(--svg-color--a8a5b0, #A8A5B0);
  stop-opacity: 0;
}

.y_-s2_b4a {
  stop-color: var(--svg-color--e0dfe4, #E0DFE4);
}

.y0cbcvb2f {
  stop-color: var(--svg-color--b4a0c9, #B4A0C9);
}

.y2zrw-j-v {
  cx: 9.303px;
  cy: 22.616px;
  r: 5.416px;
}

.yb_9u_b1r {
  stop-color: var(--svg-color--93919b, #93919B);
}

.zj2tbybeq {
  stop-color: var(--svg-color--dfd4ec, #DFD4EC);
  stop-opacity: 0;
}

.zyy6vkbhq {
  stop-color: var(--svg-color--ab93c0, #AB93C0);
}

</style>
