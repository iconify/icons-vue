<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i725SXo)" class="b3_9_mb1i"/><path fill="url(#i8VEe0b)" class="b3_9_mb1i"/><path fill="url(#iC1HaFd)" class="b3_9_mb1i"/><path fill="url(#iiIs51c)" class="b3_9_mb1i"/><path fill="url(#iTJHsjA)" class="b3_9_mb1i"/><path fill="url(#icRAEGb)" class="b3_9_mb1i"/><path fill="url(#i6XSJjd)" class="b3_9_mb1i"/><path fill="url(#iiUcNqd)" class="b3_9_mb1i"/><path fill="url(#iGeJ2wb)" class="b3_9_mb1i"/><path fill="url(#i7j0aJd)" class="b3_9_mb1i"/><path fill="url(#itdx0he)" class="b3_9_mb1i"/><path fill="url(#iGIztgd)" class="b3_9_mb1i"/><path fill="url(#iIRoYmb)" class="b3_9_mb1i"/><path fill="url(#iFGsMwc)" class="b3_9_mb1i"/><path fill="url(#iP8BILb)" class="b3_9_mb1i"/><defs><radialGradient id="iC1HaFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.62263 -1.62947 2.15859 2.14952 28.497 4.055)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="nzs4wmbyy"/><stop offset="1" class="hzdpjtb-e"/></radialGradient><radialGradient id="iiIs51c" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.29106 -7.95896 0 16.147 15.209)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="nd2ndlbnr"/><stop offset="1" class="tscq3fa3h"/></radialGradient><radialGradient id="iTJHsjA" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.5 16)scale(3)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="nd2ndlbnr"/><stop offset="1" class="tscq3fa3h"/></radialGradient><radialGradient id="icRAEGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 2 -2 -1.5 18.5 14)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="nd2ndlbnr"/><stop offset="1" class="tscq3fa3h"/></radialGradient><radialGradient id="i6XSJjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.30285 -4.3151 0 5.107 28.064)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="rj9p39btl"/></radialGradient><radialGradient id="iiUcNqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.55316 -4.78413 0 27.235 28.314)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="rj9p39btl"/></radialGradient><radialGradient id="iGeJ2wb" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 2.5 -3.53261 6.3587 1.5 3.5)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><radialGradient id="i7j0aJd" cx="0" cy="0" r="1" gradientTransform="matrix(1 4 -5.65218 1.41304 4.5 .5)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><radialGradient id="itdx0he" cx="0" cy="0" r="1" gradientTransform="matrix(1 -4 5.65218 1.41304 5 31.5)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><radialGradient id="iGIztgd" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -2 2.82609 6.3587 .5 28.5)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><radialGradient id="iIRoYmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50003 -3.5 4.94564 -2.1196 26.5 32)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><radialGradient id="iFGsMwc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50001 .99998 -1.98 -4.95011 31.5 28.5)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><radialGradient id="iP8BILb" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -2 3.96007 -3.96007 29.5 30)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="haogwie1v"/><stop offset="1" class="ck0ir8bhw"/></radialGradient><linearGradient id="i725SXo" x1="17.563" x2="24.817" y1="7.585" y2="14.839" gradientUnits="userSpaceOnUse"><stop offset=".206" class="c38v941hd"/><stop offset=".269" class="wrio88bow"/><stop offset=".341" class="otoaigb5r"/><stop offset=".457" class="jkt1y1bja"/><stop offset=".636" class="jsbvngbnz"/><stop offset=".812" class="m7c_z43bs"/></linearGradient><linearGradient id="i8VEe0b" x1="14.071" x2="8.328" y1="6.71" y2="12.453" gradientUnits="userSpaceOnUse"><stop offset=".231" class="jiuneabph"/><stop offset=".305" class="rayrvw4kp"/><stop offset=".405" class="r1sl4jxzs"/><stop offset=".471" class="nq01fuzed"/><stop offset=".682" class="hj2xkwbae"/><stop offset=".906" class="ugq2_ublb"/><stop offset=".922" class="ugq2_ublb"/><stop offset="1" class="t7qqt9byh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:multiply" /></template>
<style>
.b3_9_mb1i {
  d: path("M7.397 2.893a3.07 3.07 0 0 0-4.33 0a3.084 3.084 0 0 0 0 4.34l8.218 8.213a.75.75 0 0 1 0 1.06l-8.208 8.217a3.07 3.07 0 0 0 0 4.33a3.07 3.07 0 0 0 4.33 0l8.211-8.215a.75.75 0 0 1 1.06 0l8.21 8.205a3.07 3.07 0 0 0 4.33 0a3.07 3.07 0 0 0 0-4.33l-8.208-8.208a.75.75 0 0 1 0-1.06l8.217-8.222a3.07 3.07 0 0 0 0-4.33c-1.2-1.19-3.15-1.19-4.34 0l-8.21 8.218a.75.75 0 0 1-1.061 0z");
}

.c38v941hd {
  stop-color: var(--svg-color--4e4478, #4E4478);
}

.ck0ir8bhw {
  stop-color: var(--svg-color--7e5fcd, #7E5FCD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.haogwie1v {
  stop-color: var(--svg-color--41366a, #41366A);
}

.hj2xkwbae {
  stop-color: var(--svg-color--7664b9, #7664B9);
}

.hzdpjtb-e {
  stop-color: var(--svg-color--8a7acc, #8A7ACC);
  stop-opacity: 0;
}

.jiuneabph {
  stop-color: var(--svg-color--9e94d5, #9E94D5);
  stop-opacity: 0;
}

.jkt1y1bja {
  stop-color: var(--svg-color--7968bb, #7968BB);
}

.jsbvngbnz {
  stop-color: var(--svg-color--7948d8, #7948D8);
}

.m7c_z43bs {
  stop-color: var(--svg-color--5b38b1, #5B38B1);
}

.nd2ndlbnr {
  stop-color: var(--svg-color--7867ba, #7867BA);
}

.nq01fuzed {
  stop-color: var(--svg-color--9d93d3, #9D93D3);
}

.nzs4wmbyy {
  stop-color: var(--svg-color--a398d8, #A398D8);
}

.otoaigb5r {
  stop-color: var(--svg-color--796bb5, #796BB5);
}

.r1sl4jxzs {
  stop-color: var(--svg-color--9d93d5, #9D93D5);
}

.rayrvw4kp {
  stop-color: var(--svg-color--aba1e4, #ABA1E4);
  stop-opacity: 0.588;
}

.rj9p39btl {
  stop-color: var(--svg-color--7d6cbb, #7D6CBB);
  stop-opacity: 0;
}

.t7qqt9byh {
  stop-color: var(--svg-color--635994, #635994);
  stop-opacity: 0;
}

.tscq3fa3h {
  stop-color: var(--svg-color--7866ba, #7866BA);
  stop-opacity: 0;
}

.ugq2_ublb {
  stop-color: var(--svg-color--7f3ddc, #7F3DDC);
}

.wrio88bow {
  stop-color: var(--svg-color--685b9f, #685B9F);
}

.yv0g24i-p {
  stop-color: var(--svg-color--9447fe, #9447FE);
}

</style>
