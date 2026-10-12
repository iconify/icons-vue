<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tdz7xu-2a"/><circle class="i51s6__iq"/><path class="zp8v1ob4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tower-clock-sharp" /></template>
<style>
.i51s6__iq {
  cx: 12px;
  cy: 12.5px;
  r: 2.5px;
}

.tdz7xu-2a {
  d: path("M7 20.5V9l.48-.58l.29-.34q.48-.58.94-1.17l2.83-3.57l.46-.59l.46.59l2.83 3.57q.46.59.94 1.17l.29.34L17 9v12.25H7z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zp8v1ob4c {
  d: path("M12 11.25v1.25l.75.75m-2 8v-3h2.5v3");
}

</style>
