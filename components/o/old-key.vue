<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDsK65c)"><path fill="url(#i3t1PsE)" class="qqi1vxb3f"/></g><g filter="url(#iPy3xie)"><path fill="url(#iV2DTcc)" class="ad5zixr9p"/></g><g filter="url(#iuMafFb)"><path fill="url(#issoc2d)" clip-rule="evenodd" class="h06m2zb_o"/></g><rect fill="url(#ihrnbge)" transform="rotate(45 13.28 14.242)" class="r3d9txkac"/><rect fill="url(#it8uSXc)" transform="rotate(45 13.28 14.242)" class="r3d9txkac"/><rect fill="url(#iAUXN6b)" transform="rotate(45 13.28 14.242)" class="r3d9txkac"/><rect fill="url(#iknSsdb)" transform="rotate(45 14.36 13.162)" class="m95y62bqs"/><rect fill="url(#iPXuM2b)" transform="rotate(45 14.36 13.162)" class="m95y62bqs"/><rect fill="url(#igykGlj)" transform="rotate(45 14.36 13.162)" class="m95y62bqs"/><g filter="url(#i7Lkdud)"><circle stroke="url(#iHwxSTU)" class="kklhufbpc"/><circle stroke="url(#i1ITold)" class="kklhufbpc"/></g><defs><linearGradient id="i3t1PsE" x1="11.632" x2="9.632" y1="27.875" y2="25.709" gradientUnits="userSpaceOnUse"><stop class="jh__bdkjb"/><stop offset=".908" class="qa2byzbhy"/></linearGradient><linearGradient id="iV2DTcc" x1="8.038" x2="11.279" y1="21.031" y2="24.188" gradientUnits="userSpaceOnUse"><stop class="l68_ebwui"/><stop offset="1" class="n63s0ki7x"/></linearGradient><linearGradient id="issoc2d" x1="21.882" x2="21.882" y1="2.813" y2="18" gradientUnits="userSpaceOnUse"><stop class="qlqgjsbyd"/><stop offset="1" class="jny97c5tl"/></linearGradient><linearGradient id="ihrnbge" x1="14.087" x2="18.329" y1="15.107" y2="15.152" gradientUnits="userSpaceOnUse"><stop class="vr3w0p6kg"/><stop offset="1" class="ulnnbwb7y"/></linearGradient><linearGradient id="iAUXN6b" x1="16.683" x2="16.678" y1="15.98" y2="15.322" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fpk311b-j"/><stop offset="1" class="cjrbs5bbc"/></linearGradient><linearGradient id="iknSsdb" x1="15.167" x2="19.41" y1="14.027" y2="14.071" gradientUnits="userSpaceOnUse"><stop class="vr3w0p6kg"/><stop offset="1" class="ulnnbwb7y"/></linearGradient><linearGradient id="igykGlj" x1="17.764" x2="17.759" y1="14.9" y2="14.241" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fpk311b-j"/><stop offset="1" class="lc8czkbum"/></linearGradient><linearGradient id="iHwxSTU" x1="27.32" x2="21.468" y1="4.298" y2="9.259" gradientUnits="userSpaceOnUse"><stop class="se1yekn7e"/><stop offset="1" class="elhazhbvl"/></linearGradient><linearGradient id="i1ITold" x1="17.632" x2="19.007" y1="14" y2="11.813" gradientUnits="userSpaceOnUse"><stop class="c6_t4rbnj"/><stop offset="1" class="uniuecbkk"/></linearGradient><filter id="iDsK65c" width="8.635" height="8.752" x="6.118" y="21.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.592157 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23735"/></filter><filter id="iPy3xie" width="17.049" height="17.549" x="2.754" y="11.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.541176 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23735"/></filter><filter id="iuMafFb" width="15.938" height="16.337" x="13.913" y="1.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.505882 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23735"/></filter><filter id="i7Lkdud" width="16.368" height="16.368" x="14.125" y="1.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23735" stdDeviation=".625"/></filter><radialGradient id="it8uSXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01573 .32677 -1.89283 -.09112 16.743 14.626)" gradientUnits="userSpaceOnUse"><stop class="fpbux0f5k"/><stop offset="1" class="kgr77v3wg"/></radialGradient><radialGradient id="iPXuM2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.01573 .32677 -1.89283 -.09112 17.823 13.545)" gradientUnits="userSpaceOnUse"><stop class="rvc_nzxtj"/><stop offset="1" class="nnv95ibrf"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-key" /></template>
<style>
.ad5zixr9p {
  d: path("m16.397 12.172l3.407 3.406L6.865 28.516a2.409 2.409 0 0 1-3.406-3.407z");
}

.c6_t4rbnj {
  stop-color: var(--svg-color--feb765, #FEB765);
}

.cjrbs5bbc {
  stop-color: var(--svg-color--ec9b4f, #EC9B4F);
  stop-opacity: 0;
}

.elhazhbvl {
  stop-color: var(--svg-color--ffdd67, #FFDD67);
  stop-opacity: 0;
}

.fpbux0f5k {
  stop-color: var(--svg-color--fcbc66, #FCBC66);
}

.fpk311b-j {
  stop-color: var(--svg-color--e29226, #E29226);
}

.ft5dv1b6b {
  fill: none;
}

.h06m2zb_o {
  fill-rule: evenodd;
  d: path("M21.882 18a7.969 7.969 0 1 0 0-15.937a7.969 7.969 0 0 0 0 15.937m0-4a3.969 3.969 0 1 0 0-7.937a3.969 3.969 0 0 0 0 7.937");
}

.jh__bdkjb {
  stop-color: var(--svg-color--f4b954, #F4B954);
}

.jny97c5tl {
  stop-color: var(--svg-color--ed9953, #ED9953);
}

.kgr77v3wg {
  stop-color: var(--svg-color--fcbc66, #FCBC66);
  stop-opacity: 0;
}

.kklhufbpc {
  cx: 22.309px;
  cy: 9.604px;
  r: 6.309px;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
}

.l68_ebwui {
  stop-color: var(--svg-color--f7c250, #F7C250);
}

.lc8czkbum {
  stop-color: var(--svg-color--e29226, #E29226);
  stop-opacity: 0;
}

.m95y62bqs {
  width: 6.165px;
  height: 1.528px;
  x: 14.361px;
  y: 13.162px;
  rx: 0.764px;
}

.n63s0ki7x {
  stop-color: var(--svg-color--f8ab54, #F8AB54);
}

.nnv95ibrf {
  stop-color: var(--svg-color--fbb865, #FBB865);
  stop-opacity: 0;
}

.qa2byzbhy {
  stop-color: var(--svg-color--eca84f, #ECA84F);
}

.qlqgjsbyd {
  stop-color: var(--svg-color--f8cf4d, #F8CF4D);
}

.qqi1vxb3f {
  d: path("m6.118 26.455l5.047-5.047l3.21 3.211a1.286 1.286 0 0 1-1.039 2.19l-1.08-.11a.87.87 0 0 0-.954.931l.084 1.072a1.214 1.214 0 0 1-2.069.952z");
}

.r3d9txkac {
  width: 6.165px;
  height: 1.528px;
  x: 13.28px;
  y: 14.242px;
  rx: 0.764px;
}

.rvc_nzxtj {
  stop-color: var(--svg-color--fbb865, #FBB865);
}

.se1yekn7e {
  stop-color: var(--svg-color--ffdd67, #FFDD67);
}

.ulnnbwb7y {
  stop-color: var(--svg-color--ea994d, #EA994D);
}

.uniuecbkk {
  stop-color: var(--svg-color--feb765, #FEB765);
  stop-opacity: 0;
}

.vr3w0p6kg {
  stop-color: var(--svg-color--f6bf4e, #F6BF4E);
}

</style>
