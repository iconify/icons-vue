<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="zpmtr0f-y"><path class="jtujm970n"/><path class="sm9ws8wen"/></g><path class="qy1lvqbzf"/><path class="ma64y2b-m"/><g transform="translate(16)"><circle class="oi0tuhbin"/><path class="jdwh-hbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:right-pointing-magnifying-glass" /></template>
<style>
.jdwh-hbfb {
  fill: var(--svg-color--27a8e0, #27a8e0);
  d: path("M31.34 8.961a15.19 15.19 0 0 1 6.855 12.709c0 8.4-6.811 15.214-15.214 15.214c-.148 0-.297-.021-.445-.024C37.46 29.463 33.774 14.104 31.34 8.961");
}

.jtujm970n {
  d: path("M18.354 63.39c1.554.746 3.037.886 3.314.308l15.972-33.1c.277-.577-.753-1.654-2.31-2.405c-1.551-.747-3.041-.889-3.316-.308l-15.969 33.09c-.277.577.758 1.658 2.309 2.408");
}

.ma64y2b-m {
  fill: var(--svg-color--1e75bb, #1e75bb);
  d: path("M21.62 21.704c0 9.588 7.773 17.355 17.357 17.355c9.58 0 17.355-7.767 17.355-17.355c0-9.59-7.775-17.355-17.355-17.355c-9.584 0-17.357 7.764-17.357 17.355");
}

.oi0tuhbin {
  cx: 22.977px;
  cy: 21.704px;
  r: 15.214px;
  fill: var(--svg-color--57c6e9, #57c6e9);
}

.qy1lvqbzf {
  fill: var(--svg-color--30434a, #30434a);
  d: path("M19.476 21.704c0 10.772 8.737 19.497 19.5 19.497c10.766 0 19.498-8.725 19.498-19.497c0-10.776-8.732-19.496-19.498-19.496c-10.763 0-19.5 8.719-19.5 19.496");
}

.sm9ws8wen {
  d: path("M17.271 21.704c0 11.996 9.724 21.704 21.706 21.704c11.984 0 21.706-9.708 21.706-21.704S50.961 0 38.977 0C26.995 0 17.271 9.708 17.271 21.704");
}

.zpmtr0f-y {
  fill: var(--svg-color--243438, #243438);
}

</style>
