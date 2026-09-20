<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="k01-5vt_r"/><g class="ylewcdbqx"><circle class="bigqhibhi"/><path class="ypi26cbug"/><circle class="sozyd4b1j"/></g><circle class="wui5srd9a"/><circle class="s3twtubgi"/><path class="bu3zg-o0d"/><circle class="xhbunlb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:yin-yang" /></template>
<style>
.bigqhibhi {
  cx: 64px;
  cy: 64px;
  r: 48.47px;
  fill: none;
}

.bu3zg-o0d {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.08 64c-.02-29.78 24.11-53.93 53.88-53.95c29.78-.02 53.93 24.1 53.95 53.88c.01 14.89-12.05 26.97-26.94 26.98c-14.88.01-26.31-11.97-26.97-26.95c-.65-14.73-12.09-26.95-26.98-26.94S10.07 49.11 10.08 64");
}

.k01-5vt_r {
  cx: 64px;
  cy: 64px;
  r: 61.5px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  stroke: var(--svg-color--464747, #464747);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4px, 4px);
}

.s3twtubgi {
  cx: 34.48px;
  cy: 64.02px;
  r: 7.15px;
  fill: var(--svg-color--fff, #fff);
}

.sozyd4b1j {
  cx: 64px;
  cy: 64px;
  r: 10.09px;
  fill: var(--svg-color--fff, #fff);
}

.wui5srd9a {
  cx: 64px;
  cy: 64px;
  r: 61.5px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.xhbunlb_t {
  cx: 93.52px;
  cy: 63.98px;
  r: 7.15px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.ylewcdbqx {
  stroke: var(--svg-color--4589f1, #4589f1);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--8px, 8px);
}

.ypi26cbug {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M64 7.43v113.14M24 24l80 80M7.43 64h113.14M24 104l80-80");
}

</style>
