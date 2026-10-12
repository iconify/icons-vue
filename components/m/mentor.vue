<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="u_kome95k"/><path class="htne8un4m"/><circle class="c5-q3ob3s"/><path class="d6ueut7md"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mentor" /></template>
<style>
.c5-q3ob3s {
  cx: 5.75px;
  cy: 12px;
  r: 2.25px;
}

.d6ueut7md {
  d: path("M2.75 21.25v-1.5a3 3 0 0 1 6 0v1.5ZM5.9 3.31l.28.57q.16.31.5.36l.63.09q.34.05.09.3l-.45.43q-.25.25-.19.59l.11.62q.06.35-.25.19l-.56-.3q-.31-.16-.62 0l-.56.3q-.31.16-.25-.19l.11-.62q.06-.34-.19-.59l-.45-.43q-.25-.25.09-.3l.63-.09q.34-.05.5-.36l.28-.57q.15-.31.3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htne8un4m {
  d: path("M12.75 21.25v-3a4.25 4.25 0 0 1 8.5 0v3Z");
}

.u_kome95k {
  cx: 17px;
  cy: 7.5px;
  r: 2.75px;
}

</style>
