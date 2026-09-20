<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cuy5ac7ov"/><path class="m0kgkmred"/><path class="znjzifb8g"/><path class="mbtxbir5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:white-heavy-check-mark" /></template>
<style>
.cuy5ac7ov {
  fill: var(--svg-color--689f38, #689f38);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.m0kgkmred {
  fill: var(--svg-color--7cb342, #7cb342);
  d: path("M110.16 3.96h-98.2a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

.mbtxbir5r {
  fill: var(--svg-color--fbf9f9, #fbf9f9);
  d: path("M43.26 109.46a8.86 8.86 0 0 1-8.7-6.2l-15.1-45.5c-1.46-4.81 1.26-9.9 6.07-11.36c4.65-1.41 9.59 1.08 11.23 5.66l9.8 29.5l47.1-59.6c3.12-3.95 8.85-4.62 12.8-1.5s4.62 8.85 1.5 12.8l-57.6 72.7a9.09 9.09 0 0 1-7.1 3.5");
}

.znjzifb8g {
  fill: var(--svg-color--fff, #fff);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
