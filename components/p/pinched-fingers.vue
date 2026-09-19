<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pky6wga5j"/><path fill="url(#iGbAGtb)" class="eh-6t5fyc"/><path fill="url(#iXHFOIc)" class="eh-6t5fyc"/><path fill="url(#iDiYWJb)" class="eh-6t5fyc"/><path fill="url(#iVKwHnb)" class="eh-6t5fyc"/><g filter="url(#i9rufDb)"><path class="bhzdpdi1p"/><path fill="url(#iLw55wd)" class="xb0mgyvwa"/><path fill="url(#iIlCmCd)" class="xb0mgyvwa"/><path fill="url(#i3fQW6c)" class="xb0mgyvwa"/><path fill="url(#irB9pjb)" class="xb0mgyvwa"/></g><path fill="url(#icmVczc)" class="aiwcy8bgo"/><path fill="url(#i48tKlz)" class="h22filbgm"/><path fill="url(#iEGyDDe)" class="h22filbgm"/><g filter="url(#icbbYFc)"><path stroke="url(#ivkh5dd)" class="p9-088t7p"/></g><defs><radialGradient id="iGbAGtb" cx="0" cy="0" r="1" gradientTransform="matrix(4.21875 -.35937 .48802 5.72894 18.719 4.219)" gradientUnits="userSpaceOnUse"><stop class="zl8wxsb8h"/><stop offset="1" class="jnq3rwbwn"/></radialGradient><radialGradient id="iXHFOIc" cx="0" cy="0" r="1" gradientTransform="rotate(-32.25 29.997 -35.324)scale(4.48566 10.4433)" gradientUnits="userSpaceOnUse"><stop class="zl8wxsb8h"/><stop offset=".948" class="jnq3rwbwn"/></radialGradient><radialGradient id="iDiYWJb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.731 31.443 -8.659)scale(8.57053 2.66744)" gradientUnits="userSpaceOnUse"><stop class="zl8wxsb8h"/><stop offset="1" class="jnq3rwbwn"/></radialGradient><radialGradient id="iVKwHnb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.375 -15.87497 8.3679 -5.9959 31.188 17.594)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="gvgfvck1n"/><stop offset="1" class="kgsovmdua"/></radialGradient><radialGradient id="iLw55wd" cx="0" cy="0" r="1" gradientTransform="rotate(-23.656 59.681 13.277)scale(30.9972 29.5828)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="s5nxcmb-w"/><stop offset="1" class="v01hembdp"/></radialGradient><radialGradient id="iIlCmCd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50242 5.60395 -3.9277 -2.45478 18.968 17.805)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="acwb59b8o"/><stop offset="1" class="c-434fjgh"/></radialGradient><radialGradient id="i3fQW6c" cx="0" cy="0" r="1" gradientTransform="matrix(10.414 0 0 5.43789 2.25 23.83)" gradientUnits="userSpaceOnUse"><stop class="v-e2hqwul"/><stop offset="1" class="kvolyw2fr"/></radialGradient><radialGradient id="irB9pjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.05479 3.5407 -3.62102 2.1014 9.02 16.74)" gradientUnits="userSpaceOnUse"><stop class="bj7t0-28h"/><stop offset="1" class="sckw28ain"/></radialGradient><radialGradient id="icmVczc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81252 2.74999 -4.21793 -2.78005 20.563 6.875)" gradientUnits="userSpaceOnUse"><stop class="a3cahccfh"/><stop offset="1" class="vxqukf7is"/></radialGradient><radialGradient id="i48tKlz" cx="0" cy="0" r="1" gradientTransform="matrix(5.03125 .0625 -.06485 5.22067 19.969 13.656)" gradientUnits="userSpaceOnUse"><stop class="k6-u6bb0f"/><stop offset="1" class="n75khhb5y"/></radialGradient><radialGradient id="iEGyDDe" cx="0" cy="0" r="1" gradientTransform="matrix(3.08216 -.98069 1.24583 3.91547 19.622 10.24)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="ne-gglbjf"/><stop offset="1" class="hq2wyd0hj"/></radialGradient><filter id="i9rufDb" width="26.58" height="27.521" x="2" y="2.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.521569 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1880"/></filter><filter id="icbbYFc" width="11.961" height="16.255" x="16.934" y="9.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1880" stdDeviation=".75"/></filter><linearGradient id="ivkh5dd" x1="26.907" x2="24.539" y1="16.171" y2="26.251" gradientUnits="userSpaceOnUse"><stop class="gophtjlrd"/><stop offset="1" class="oajc4e91r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinched-fingers" /></template>
<style>
.a3cahccfh {
  stop-color: var(--svg-color--ffe53f, #FFE53F);
}

.acwb59b8o {
  stop-color: var(--svg-color--ffe031, #FFE031);
}

.aiwcy8bgo {
  d: path("M16.21 7.843a2.886 2.886 0 0 1 4.995 2.892l-4.314 7.718c-.799 1.38-2.557 1.574-3.937.775c-1.38-.798-1.897-2.517-1.099-3.896z");
}

.bhzdpdi1p {
  fill: var(--svg-color--ffbd3c, #FFBD3C);
  d: path("M22.29 3.88c-.39-.24-.85-.38-1.33-.4A2.68 2.68 0 0 0 18.22 6c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68M18.03 16.8c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.bj7t0-28h {
  stop-color: var(--svg-color--e19b38, #E19B38);
}

.c-434fjgh {
  stop-color: var(--svg-color--ffe031, #FFE031);
  stop-opacity: 0;
}

.eh-6t5fyc {
  d: path("M23.24 2.4c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.ft5dv1b6b {
  fill: none;
}

.gophtjlrd {
  stop-color: var(--svg-color--ffe338, #FFE338);
}

.gvgfvck1n {
  stop-color: var(--svg-color--d6b05c, #D6B05C);
  stop-opacity: 0;
}

.h22filbgm {
  d: path("M28.08 14.56a12.4 12.4 0 0 1-.566 3.69l-5.608 6.031l-2.562-6.031l-.017-.044q.05.004.103.004c1.76 0 3.24-1.34 3.38-3.09l.001-.027c.01-.18.019-.352.019-.533c0-1.493-.475-2.916-1.426-4.24a2.89 2.89 0 0 0-1.25-3.529c-.67-.388-1.263-.416-1.924-.351v-.014a2.682 2.682 0 0 1 2.73-2.946c.48.02.94.16 1.33.4c.24.16 5.8 3.91 5.79 10.68");
}

.hq2wyd0hj {
  stop-color: var(--svg-color--da7834, #DA7834);
  stop-opacity: 0;
}

.jnq3rwbwn {
  stop-color: var(--svg-color--d59430, #D59430);
  stop-opacity: 0;
}

.k6-u6bb0f {
  stop-color: var(--svg-color--e78923, #E78923);
}

.kgsovmdua {
  stop-color: var(--svg-color--d6b05c, #D6B05C);
}

.kvolyw2fr {
  stop-color: var(--svg-color--ffd231, #FFD231);
  stop-opacity: 0;
}

.n75khhb5y {
  stop-color: var(--svg-color--e78923, #E78923);
  stop-opacity: 0;
}

.ne-gglbjf {
  stop-color: var(--svg-color--da7834, #DA7834);
}

.oajc4e91r {
  stop-color: var(--svg-color--ffe338, #FFE338);
  stop-opacity: 0;
}

.p9-088t7p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M26.346 12.248c.514 4.95-3.035 10.087-6.911 11.255");
}

.pky6wga5j {
  fill: var(--svg-color--ffe643, #FFE643);
  d: path("M23.24 2.4c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.s5nxcmb-w {
  stop-color: var(--svg-color--ffe749, #FFE749);
  stop-opacity: 0;
}

.sckw28ain {
  stop-color: var(--svg-color--e19b38, #E19B38);
  stop-opacity: 0;
}

.v-e2hqwul {
  stop-color: var(--svg-color--ffd231, #FFD231);
}

.v01hembdp {
  stop-color: var(--svg-color--ffe749, #FFE749);
}

.vxqukf7is {
  stop-color: var(--svg-color--ffe53f, #FFE53F);
  stop-opacity: 0;
}

.xb0mgyvwa {
  d: path("M22.29 3.88c-.39-.24-.85-.38-1.33-.4A2.68 2.68 0 0 0 18.22 6c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68M18.03 16.8c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.zl8wxsb8h {
  stop-color: var(--svg-color--d59430, #D59430);
}

</style>
