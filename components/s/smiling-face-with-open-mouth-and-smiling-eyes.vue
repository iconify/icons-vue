<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<symbol id="ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesh" viewBox="-64.5 -64.5 129 129"><g class="bqzt8ngox"><path class="nes8vjytg"/><path class="o2qzm0b0x"/><path class="ytyxx4q3b"/><path class="htano6txl"/><path class="hglg8acvx"/><path class="t49x-q1ug"/><path class="fzv3msbsm"/><path class="j7_d0nbzc"/></g></symbol><linearGradient id="ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesa" x1="64" x2="64" y1="19.717" y2="107.7" gradientUnits="userSpaceOnUse"><stop offset=".5" class="rsmbf9bdq"/><stop offset=".612" class="p0_jflzej"/><stop offset=".708" class="xj6qgfb6d"/><stop offset=".797" class="uxvedvbhm"/><stop offset=".883" class="qnth-c2kd"/><stop offset=".9" class="qu1llccgx"/></linearGradient><path fill="url(#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesa)" class="z5pvlv0ga"/><path class="mk3s0l27t"/><defs><path id="ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesb" class="o_nn23bzk"/></defs><clipPath id="ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesc"><use xlink:href="#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesb"/></clipPath><path clip-path="url(#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesc)" class="pdwpa-bfj"/><path clip-path="url(#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesc)" class="q2n_12bdp"/><path clip-path="url(#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesc)" class="iw90q-b5s"/><g clip-path="url(#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesc)"><defs><path id="ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesd" class="jddsrikyy"/></defs><clipPath id="ssvg-id-smiling-face-with-open-mouth-and-smiling-eyese"><use xlink:href="#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyesd"/></clipPath><g clip-path="url(#ssvg-id-smiling-face-with-open-mouth-and-smiling-eyese)"><path class="at35vzcjh"/></g></g><g class="g5qpdebxn"><path class="w8idntjxd"/><path class="j46h0xb1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:smiling-face-with-open-mouth-and-smiling-eyes" /></template>
<style>
.at35vzcjh {
  d: path("M106.79 63.09c.07 0 .14.07.14.12-1.68 8.85-6.6 16.96-13.85 22.84-7.97 6.46-18.21 9.88-29.63 9.88-10.46 0-20.64-3.45-28.67-9.72-7.72-6.03-12.96-14.19-14.76-23.02.01-.02.07-.1.18-.1h.01c12.86 2.38 27.82 3.64 43.26 3.64s30.41-1.26 43.28-3.65c.01.01.03.01.04.01m0-4.21c-.27 0-.54.02-.81.08-12.18 2.26-26.79 3.58-42.51 3.58-15.71 0-30.31-1.32-42.49-3.57-.27-.05-.54-.08-.81-.08-2.67 0-4.83 2.44-4.27 5.18 4.04 19.81 23.55 36.08 47.55 36.08 26.27 0 43.94-16.8 47.61-36.15.52-2.72-1.63-5.12-4.27-5.12z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.bqzt8ngox {
  fill: none;
  stroke: var(--svg-color--4285f4, #4285F4);
  stroke-miterlimit: 10;
}

.fzv3msbsm {
  d: path("M15.99 48.91v-97.84");
}

.g5qpdebxn {
  fill: var(--svg-color--242424, #242424);
}

.hglg8acvx {
  d: path("M-.01 51V-51");
}

.htano6txl {
  d: path("M0-43c-12.29 0-23.54 3.94-31.68 11.09C-40.39-24.25-45-13.21-45 0c0 29.7 22.6 43 45 43 21.67 0 45-13.46 45-43S21.67-43 0-43z");
}

.iw90q-b5s {
  d: path("M63.48 86.42c-11.78 0-22.05 6.42-27.53 15.95 7.12 3.89 16.83 6.29 27.53 6.29s20.41-2.4 27.53-6.29c-5.48-9.53-15.75-15.95-27.53-15.95z");
  fill: var(--svg-color--ed7770, #ED7770);
}

.j46h0xb1a {
  d: path("M88.26 47.08s-.06-.07-.16-.21c-.1-.13-.25-.33-.45-.57-.16-.17-.35-.37-.57-.6-.23-.26-.5-.52-.77-.79-.28-.26-.58-.53-.88-.76-.3-.24-.62-.42-.88-.57-.27-.16-.52-.21-.69-.26-.09-.04-.16-.03-.22-.04-.03.01-.06-.01-.09 0l-.04.01h-.04c.13 0-.29.01.29-.01l-.58.02c-.15 0-.05.01-.04.01.03 0 .05 0 .08-.01.09-.03 0 0-.03 0-.04 0-.08.01-.12.03-.16.05-.42.1-.69.26-.27.15-.58.33-.88.57-.3.23-.6.5-.88.76-.55.54-1.03 1.08-1.37 1.47-.34.4-.54.63-.54.63l-.24.28c-1.44 1.68-4.09 1.97-5.91.64-1.24-.9-1.78-2.32-1.55-3.66 0 0 .07-.43.28-1.18.22-.74.59-1.81 1.31-3.06.73-1.24 1.78-2.71 3.55-4.04.87-.66 1.94-1.31 3.2-1.74.31-.12.63-.22.97-.3.35-.09.62-.17 1.1-.24l.65-.09c.2-.03.49-.06.54-.06l.58-.04.32-.01h.1l.13.01.27.01.54.04c.36.03.7.09 1.05.15.69.13 1.37.3 1.99.53 1.26.44 2.32 1.09 3.2 1.74 1.78 1.33 2.82 2.8 3.55 4.04.37.62.64 1.2.84 1.72.22.49.38 1.02.51 1.41.12.38.12.58.16.76.03.17.05.26.05.26.39 2.12-1.17 4.13-3.48 4.49-1.66.25-3.25-.42-4.16-1.6z");
}

.j7_d0nbzc {
  d: path("M53 .08H-53");
}

.jddsrikyy {
  d: path("M10.24 46.49v14.89C26.62 71 44.6 76.35 63.48 76.35s36.86-5.35 53.24-14.97V46.49H10.24zm53.24 39.93c-11.78 0-22.05 6.42-27.53 15.95 7.12 3.89 16.83 6.29 27.53 6.29 10.71 0 20.41-2.4 27.53-6.29-5.48-9.53-15.75-15.95-27.53-15.95z");
}

.mk3s0l27t {
  d: path("M64 10.11c14.99 0 28.86 4.95 39.03 13.93C114.13 33.83 120 47.65 120 64c0 16.27-5.87 30.07-16.97 39.89-10.21 9.03-24.07 14-39.03 14-15.04 0-28.9-4.91-39.04-13.82C13.86 94.32 8 80.46 8 64c0-16.54 5.86-30.42 16.96-40.15C35.07 14.99 48.93 10.11 64 10.11m0-4c-31.15 0-60 20-60 57.89 0 37.68 28.85 57.89 60 57.89s60-20.73 60-57.89c0-37.37-28.85-57.89-60-57.89z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.nes8vjytg {
  d: path("M-64-64H64V64H-64z");
}

.o_nn23bzk {
  d: path("M63.47 62.53c-15.71 0-30.31-1.32-42.49-3.57-3.02-.56-5.69 2.1-5.08 5.11 4.04 19.81 23.55 36.08 47.55 36.08 26.27 0 43.94-16.8 47.61-36.15.57-2.99-2.1-5.6-5.09-5.04-12.18 2.25-26.78 3.57-42.5 3.57z");
}

.o2qzm0b0x {
  d: path("M36.95 37.82C27.32 46.32 14.2 51 0 51c-14.27 0-27.39-4.62-36.96-13.01C-47.45 28.79-53 15.65-53 0c0-15.58 5.55-28.69 16.04-37.92C-27.36-46.35-14.24-51 0-51c14.17 0 27.29 4.71 36.95 13.25C47.45-28.45 53-15.4 53 0c0 15.47-5.55 28.55-16.05 37.82z");
}

.p0_jflzej {
  stop-color: var(--svg-color--fede32, #FEDE32);
}

.pdwpa-bfj {
  d: path("M63.47 62.53c-15.71 0-30.31-1.32-42.49-3.57-3.02-.56-5.69 2.1-5.08 5.11 4.04 19.81 23.55 36.08 47.55 36.08 26.27 0 43.94-16.8 47.61-36.15.57-2.99-2.1-5.6-5.09-5.04-12.18 2.25-26.78 3.57-42.5 3.57z");
  fill: var(--svg-color--242424, #242424);
}

.q2n_12bdp {
  d: path("M116.72 61.38V46.49H10.24v14.89C26.61 71 44.6 76.35 63.48 76.35s36.86-5.35 53.24-14.97z");
  fill: var(--svg-color--fff, #fff);
}

.qnth-c2kd {
  stop-color: var(--svg-color--f7a924, #F7A924);
}

.qu1llccgx {
  stop-color: var(--svg-color--f6a323, #F6A323);
}

.rsmbf9bdq {
  stop-color: var(--svg-color--fee133, #FEE133);
}

.t49x-q1ug {
  d: path("M-16 48.95v-97.88");
}

.uxvedvbhm {
  stop-color: var(--svg-color--fac12b, #FAC12B);
}

.w8idntjxd {
  d: path("M48.83 47.08s-.06-.07-.17-.21c-.1-.13-.25-.33-.45-.57-.16-.17-.35-.37-.57-.6-.23-.26-.5-.52-.77-.79-.28-.26-.58-.53-.88-.76-.3-.24-.62-.42-.88-.57-.27-.16-.52-.21-.69-.26-.09-.04-.16-.03-.22-.04-.03.01-.06-.01-.09 0l-.04.01h-.04c.13 0-.29.01.29-.01l-.58.02c-.15 0-.05.01-.04.01.03 0 .05 0 .08-.01.09-.03 0 0-.03 0-.04 0-.08.01-.12.03-.16.05-.42.1-.69.26-.27.15-.58.33-.88.57-.3.23-.6.5-.88.76-.55.54-1.03 1.08-1.37 1.47-.34.4-.54.63-.54.63l-.24.28c-1.44 1.68-4.09 1.97-5.91.64-1.24-.9-1.78-2.32-1.55-3.66 0 0 .07-.43.28-1.18.22-.74.59-1.81 1.31-3.06.73-1.24 1.78-2.71 3.55-4.04.87-.66 1.94-1.31 3.2-1.74.31-.12.63-.22.97-.3.35-.09.62-.17 1.1-.24l.65-.09c.2-.03.49-.06.54-.06l.58-.04.32-.01h.1l.13.01.27.01.54.04c.36.03.7.09 1.05.15.69.13 1.37.3 1.99.53 1.26.44 2.32 1.09 3.2 1.74 1.78 1.33 2.82 2.8 3.55 4.04.37.62.64 1.2.84 1.72.22.49.38 1.02.51 1.41.12.38.12.58.16.76.03.17.05.26.05.26.39 2.12-1.17 4.13-3.48 4.49-1.65.25-3.24-.42-4.15-1.6z");
}

.xj6qgfb6d {
  stop-color: var(--svg-color--fcd32f, #FCD32F);
}

.ytyxx4q3b {
  d: path("M0 55c-29.59 0-57-19.01-57-55 0-35.8 27.41-55 57-55S57-35.31 57 0c0 35.51-27.41 55-57 55z");
}

.z5pvlv0ga {
  d: path("M64 119.89C36.07 119.89 6 102.4 6 64S36.07 8.11 64 8.11c15.48 0 29.81 5.12 40.36 14.43C115.9 32.72 122 47.06 122 64c0 16.86-6.1 31.17-17.64 41.39-10.58 9.35-24.91 14.5-40.36 14.5z");
}

</style>
