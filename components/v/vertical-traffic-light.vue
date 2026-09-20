<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dafs9jdse"/><path class="d99tdydqv"/><path class="j-7-hnbfk"/><circle class="vkkoy-b8s"/><circle class="vh5zwxb-f"/><circle class="m3xfxubnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:vertical-traffic-light" /></template>
<style>
.d99tdydqv {
  fill: var(--svg-color--757576, #757576);
  d: path("M74.06 99.46V31.25c0-14.4-11.67-26.07-26.06-26.07S21.94 16.85 21.94 31.24v68.21c0 14.39 11.67 26.06 26.06 26.06c14.39.01 26.06-11.66 26.06-26.05");
}

.dafs9jdse {
  fill: var(--svg-color--616161, #616161);
  d: path("M31.98 46.21v-7.66a6.3 6.3 0 0 1 6.3-6.3h66.4a6.3 6.3 0 0 1 6.3 6.3v7.66a6.3 6.3 0 0 1-6.3 6.3h-66.4a6.3 6.3 0 0 1-6.3-6.3m0 48.21v-7.66a6.3 6.3 0 0 1 6.3-6.3h66.4a6.3 6.3 0 0 1 6.3 6.3v7.66a6.3 6.3 0 0 1-6.3 6.3h-66.4c-3.48-.01-6.3-2.83-6.3-6.3");
}

.j-7-hnbfk {
  fill: var(--svg-color--edece4, #edece4);
  d: path("M68.76 96.75V28.54c0-14.39-11.67-26.06-26.06-26.06S16.64 14.15 16.64 28.54v68.21c0 14.39 11.67 26.06 26.06 26.06c14.39.01 26.06-11.66 26.06-26.06");
}

.m3xfxubnp {
  cx: 42.7px;
  cy: 27.37px;
  r: 14.34px;
  fill: var(--svg-color--e43f11, #e43f11);
}

.vh5zwxb-f {
  cx: 42.7px;
  cy: 62.65px;
  r: 14.34px;
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.vkkoy-b8s {
  cx: 42.7px;
  cy: 97.93px;
  r: 14.34px;
  fill: var(--svg-color--4caf50, #4caf50);
}

</style>
