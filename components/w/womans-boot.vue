<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7w8Akb)"><path fill="url(#iCNrlWd)" class="v8stg57xx"/><path fill="url(#ibpmOsc)" class="v8stg57xx"/><path fill="url(#iBsbTOb)" class="v8stg57xx"/><path fill="url(#i5OrhBk)" class="v8stg57xx"/></g><path fill="url(#iuQVGfd)" class="nm1ekbbau"/><path fill="url(#iQU8Avc)" class="nm1ekbbau"/><path fill="url(#iMqi8Ud)" class="nm1ekbbau"/><path fill="url(#iRPn26c)" class="nm1ekbbau"/><path fill="url(#i5IR48b)" class="nm1ekbbau"/><path fill="url(#iakaP1d)" class="nm1ekbbau"/><g filter="url(#it2BSAw)"><path class="hsl-ikbrp"/></g><g filter="url(#i9VOwUb)"><path fill="url(#iN0AWnb)" class="kmfay6bpq"/><path fill="url(#imWW4He)" class="kmfay6bpq"/></g><defs><linearGradient id="iCNrlWd" x1="5" x2="26.25" y1="26.813" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="tkk62kbug"/><stop offset="1" class="tl8lkisya"/></linearGradient><linearGradient id="ibpmOsc" x1="29.781" x2="18.625" y1="29.953" y2="29.953" gradientUnits="userSpaceOnUse"><stop class="mciw7-b9m"/><stop offset="1" class="m8u1_hb6q"/></linearGradient><linearGradient id="iBsbTOb" x1="29.781" x2="28.813" y1="29.688" y2="29.688" gradientUnits="userSpaceOnUse"><stop class="a6lx6nbbx"/><stop offset="1" class="q4tw0_nms"/></linearGradient><linearGradient id="i5OrhBk" x1="1.969" x2="7.125" y1="26.031" y2="26.031" gradientUnits="userSpaceOnUse"><stop class="rtu1gcy2h"/><stop offset="1" class="ujquawbva"/></linearGradient><linearGradient id="iMqi8Ud" x1="16" x2="16" y1="2" y2="3.688" gradientUnits="userSpaceOnUse"><stop class="n_-m_2ysr"/><stop offset="1" class="ib8fw0b4c"/></linearGradient><linearGradient id="iRPn26c" x1="1.75" x2="8" y1="17.375" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="xj--tnbab"/><stop offset="1" class="h41xcyvek"/></linearGradient><linearGradient id="iN0AWnb" x1="7.078" x2="8.781" y1="2" y2="11.156" gradientUnits="userSpaceOnUse"><stop class="kp6vz7b0s"/><stop offset="1" class="h9p30ccqd"/></linearGradient><linearGradient id="imWW4He" x1="5.406" x2="7.344" y1="3.719" y2="3.75" gradientUnits="userSpaceOnUse"><stop offset=".298" class="ymzm_f4hw"/><stop offset="1" class="n-ay8yk7c"/></linearGradient><radialGradient id="iuQVGfd" cx="0" cy="0" r="1" gradientTransform="rotate(133.813 8.676 11.787)scale(17.0626 22.0729)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="z2ubpb-up"/><stop offset="1" class="db2fzm5wv"/></radialGradient><radialGradient id="iQU8Avc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.75 0 0 -2.135 18.063 3.563)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="olps03shj"/><stop offset="1" class="q_6e1bcod"/></radialGradient><radialGradient id="i5IR48b" cx="0" cy="0" r="1" gradientTransform="matrix(-9.15625 0 0 -8.4375 29.781 25.938)" gradientUnits="userSpaceOnUse"><stop class="kcu60ntzl"/><stop offset="1" class="dbqc14b_k"/></radialGradient><radialGradient id="iakaP1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 2.25 -4.2865 -1.54788 24.125 20)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="f7g21jmzm"/><stop offset="1" class="qdlkwwb0x"/></radialGradient><filter id="i7w8Akb" width="27.663" height="11.537" x="2.219" y="18.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.584314 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17374"/></filter><filter id="it2BSAw" width="5.063" height="14.922" x="4.219" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17374" stdDeviation=".75"/></filter><filter id="i9VOwUb" width="2.131" height="12.766" x="5.963" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17374"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:womans-boot" /></template>
<style>
.a6lx6nbbx {
  stop-color: var(--svg-color--ffd08a, #FFD08A);
}

.db2fzm5wv {
  stop-color: var(--svg-color--eb305f, #EB305F);
}

.dbqc14b_k {
  stop-color: var(--svg-color--ff5ea4, #FF5EA4);
  stop-opacity: 0;
}

.f7g21jmzm {
  stop-color: var(--svg-color--f43d76, #F43D76);
}

.ft5dv1b6b {
  fill: none;
}

.h41xcyvek {
  stop-color: var(--svg-color--cb3842, #CB3842);
  stop-opacity: 0;
}

.h9p30ccqd {
  stop-color: var(--svg-color--fab27e, #FAB27E);
}

.hsl-ikbrp {
  fill: var(--svg-color--cf2942, #CF2942);
  d: path("M7.781 3.188V14.16c0 .524-.461.948-1.031.948s-1.031-.424-1.031-.948V3.188z");
}

.ib8fw0b4c {
  stop-color: var(--svg-color--ea3b5b, #EA3B5B);
  stop-opacity: 0;
}

.kcu60ntzl {
  stop-color: var(--svg-color--ff5ea4, #FF5EA4);
}

.kmfay6bpq {
  d: path("M8.094 2v11.75a1.016 1.016 0 0 1-2.031 0V2z");
}

.kp6vz7b0s {
  stop-color: var(--svg-color--f1ac67, #F1AC67);
}

.m8u1_hb6q {
  stop-color: var(--svg-color--ffd890, #FFD890);
  stop-opacity: 0;
}

.mciw7-b9m {
  stop-color: var(--svg-color--ffd890, #FFD890);
}

.n_-m_2ysr {
  stop-color: var(--svg-color--ea3b5b, #EA3B5B);
}

.n-ay8yk7c {
  stop-color: var(--svg-color--e29f5d, #E29F5D);
  stop-opacity: 0;
}

.nm1ekbbau {
  d: path("M4.219 2a2 2 0 0 0-2 2v17.375H9.97a3.654 3.654 0 0 1 3.654 3.654a2.284 2.284 0 0 0 2.284 2.284H29.78c-.147-4.908-3.579-5.747-5.625-6.247q-.343-.082-.625-.16l-.428-.117c-1.473-.4-2.573-.7-4.072-2.57c-1.055-1.316-1.121-4.217-1.125-5.756V4a2 2 0 0 0-2-2z");
}

.olps03shj {
  stop-color: var(--svg-color--ff5a80, #FF5A80);
}

.q_6e1bcod {
  stop-color: var(--svg-color--ff5a80, #FF5A80);
  stop-opacity: 0;
}

.q4tw0_nms {
  stop-color: var(--svg-color--ffd08a, #FFD08A);
  stop-opacity: 0;
}

.qdlkwwb0x {
  stop-color: var(--svg-color--f43d76, #F43D76);
  stop-opacity: 0;
}

.rtu1gcy2h {
  stop-color: var(--svg-color--ca9567, #CA9567);
}

.tkk62kbug {
  stop-color: var(--svg-color--f0a773, #F0A773);
}

.tl8lkisya {
  stop-color: var(--svg-color--ffbd8c, #FFBD8C);
}

.ujquawbva {
  stop-color: var(--svg-color--ca9567, #CA9567);
  stop-opacity: 0;
}

.v8stg57xx {
  d: path("M7.203 23.963h1.158c2.134.084 2.486 1.771 2.713 3.318c.133 1.664 1.313 2.672 2.97 2.672h14.987a.75.75 0 0 0 .75-.75v-1.902l-19.2-8.785l-4.878.93l.52 1.929H2.22v8.078a.5.5 0 0 0 .5.5h3.984a.5.5 0 0 0 .5-.5z");
}

.xj--tnbab {
  stop-color: var(--svg-color--cb3842, #CB3842);
}

.ymzm_f4hw {
  stop-color: var(--svg-color--e29f5d, #E29F5D);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

</style>
