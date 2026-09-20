<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGpNV3ne4E" cx="63.6" cy="62.9" r="56.96" fx="63.6" fy="62.9" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGpNV3ne4E)" class="x6m_cacnq"/><path class="mtcnxlbzc"/><path class="su-7w2zck"/><circle class="dnsfj4q_g"/><path class="m1_5ssbqf"/><circle class="g41uudblp"/><path class="nd8yk_xck"/><path class="bxt2erbtx"/><path class="srs208b5f"/><path class="fawxfkbin"/><path class="qj0vr3vxu"/><path class="r2qx-fb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:zany-face" /></template>
<style>
.bxt2erbtx {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M45.86 94.67v13.57c0 9.48 7.69 17.17 17.17 17.17h3.27c9.48 0 17.17-7.69 17.17-17.17V87.33c0-2.88-2.9-4.85-5.58-3.8c-3.49 1.37-8.26 3.07-13.22 4.32c-5.99 1.51-11.69 2.34-15.21 2.77a4.083 4.083 0 0 0-3.59 4.05Z");
}

.dnsfj4q_g {
  cx: 80.4px;
  cy: 41px;
  r: 7px;
  fill: var(--svg-color--422b0d, #422b0d);
}

.fawxfkbin {
  fill: var(--svg-color--fff, #fff);
  d: path("M95.34 60c-3.56 1.92-16.47 9.4-29 13.64s-27.9 6.16-31.89 6.8c-2.51.4-4.54 3.35-4.56 5.16c0 0 14.05 5.2 39.7-2.4s33.01-22.18 33.01-22.18c-1.1-1.42-5.03-2.21-7.26-1Z");
}

.g41uudblp {
  cx: 36px;
  cy: 57px;
  r: 7px;
  fill: var(--svg-color--422b0d, #422b0d);
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.m1_5ssbqf {
  fill: var(--svg-color--fff, #fff);
  d: path("M35.9 44.78c-1.52 0-3.03.3-4.55.91c-6.21 2.5-9.17 9.62-6.67 15.76c1.89 4.7 6.44 7.58 11.21 7.58c1.52 0 3.03-.3 4.55-.91c6.21-2.5 9.17-9.62 6.67-15.76c-1.89-4.7-6.36-7.58-11.21-7.58");
}

.mtcnxlbzc {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.49 29.67c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94c10.76 17.66 30.99 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5c11.5-10.2 17.6-24.5 17.6-41.4c0-12.74-3.47-24.06-10.11-33.23");
}

.nd8yk_xck {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M97.26 59.46c-3.55 1.96-18.39 9.93-30.92 14.17s-29.16 6.91-33.17 7.5s-4.42 3.56-2.32 7.87c4.85 10 23.3 22.28 45.67 14.71c22.37-7.56 29.58-28.53 27.37-39.41c-.96-4.7-3.08-6.8-6.63-4.85Z");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.qj0vr3vxu {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M101.16 58.8c-1.66-.95-3.73-.79-6.33.5c-.62.31-1.54.78-2.7 1.38c-5.39 2.8-16.61 8.61-26.16 11.84s-22 5.41-27.98 6.46c-1.28.22-2.3.4-2.98.54c-2.85.56-4.59 1.68-5.34 3.45c-1.15 2.71 1.71 7.2 2.61 8.6c.19.29.39.17.28-.17c-.24-.7-1.41-4-.49-5.94c.9-1.92 2.43-2.48 3.58-2.71c.67-.13 1.67-.31 2.92-.53c6.06-1.06 18.68-3.28 28.46-6.59s21.16-9.2 26.62-12.04c1.13-.59 2.03-1.05 2.64-1.36c1.04-.52 2.6-.99 4.49-.02c1.9.98 2.98 4.32 3.21 5.02c.11.34.35.31.32-.03c-.13-1.65-.59-6.95-3.15-8.41Z");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r2qx-fb1j {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M66.67 87.23c-.66.18-1.33.36-2 .53s-1.34.33-2 .48v19.09c0 1.1.9 2 2 2s2-.9 2-2V87.22Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.srs208b5f {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M48.89 93.38c1.53-.13 9.13-.68 15.77-2.19c5.51-1.25 9.55-2.75 13.38-4.25c2.96-1.16 4.25-.38 5.42.3c-.11-2.79-2.94-4.67-5.57-3.63c-3.49 1.37-8.26 3.07-13.22 4.32c-5.99 1.51-11.69 2.34-15.21 2.77c-2 .24-3.5 1.9-3.57 3.9c.65-.8 1.48-1.08 3.01-1.21Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.su-7w2zck {
  fill: var(--svg-color--fff, #fff);
  d: path("M80.4 22.9c7.4 0 13.9 4.4 16.7 11.2c3.7 9.2-.7 19.7-9.9 23.4c-2.2.9-4.4 1.3-6.8 1.3c-7.4 0-13.9-4.4-16.7-11.2c-3.7-9.2.7-19.7 9.9-23.4c2.3-.9 4.5-1.3 6.8-1.3");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.x6m_cacnq {
  d: path("M63.6 118.8c-27.9 0-58-17.5-58-55.9S35.7 7 63.6 7c15.5 0 29.8 5.1 40.4 14.4c11.5 10.2 17.6 24.6 17.6 41.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

</style>
