<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivtpv0i3b"/><path class="f1jeh4q_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seat-cover" /></template>
<style>
.f1jeh4q_s {
  d: path("m6.75 11l2 6.5H18");
}

.ivtpv0i3b {
  d: path("M3.5 2.5H10V6H3.5ZM6.75 6v2.5m-2 0H9q1 0 1.25 1l1.75 5h7q2 0 2 2V19q0 2-2 2H8.5q-2 0-2.25-2L3.5 9.75Q3.25 8.5 4.75 8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
