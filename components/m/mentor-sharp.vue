<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="u_kome95k"/><path class="htne8un4m"/><circle class="c5-q3ob3s"/><path class="qc6gf2bxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mentor-sharp" /></template>
<style>
.c5-q3ob3s {
  cx: 5.75px;
  cy: 12px;
  r: 2.25px;
}

.htne8un4m {
  d: path("M12.75 21.25v-3a4.25 4.25 0 0 1 8.5 0v3Z");
}

.qc6gf2bxs {
  d: path("M2.75 21.25v-1.5a3 3 0 0 1 6 0v1.5ZM5.9 3.31l.28.57l.16.31l.34.05l.63.09l.34.05l-.25.25l-.45.43l-.25.25l.06.34l.11.62l.06.35l-.31-.16l-.56-.3L5.75 6l-.31.16l-.56.3l-.31.16l.06-.35l.11-.62l.06-.34l-.25-.25l-.45-.43l-.25-.25l.34-.05l.63-.09l.34-.05l.16-.31l.28-.57l.15-.31z");
}

.u_kome95k {
  cx: 17px;
  cy: 7.5px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
