<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tb_dn91ml"/><circle class="lc9ede9dj"/><path class="ntcsy005u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ok-hand-sharp" /></template>
<style>
.lc9ede9dj {
  cx: 8.5px;
  cy: 10.75px;
  r: 1.75px;
}

.ntcsy005u {
  d: path("M14.75 5.5v6m2.5-4V12");
}

.tb_dn91ml {
  d: path("M12.25 8.75V4h2.5v1.25v-1.5h2.5V7.5V6.35h2.3V15a6.25 6.25 0 0 1-6.25 6.25h-.5A5.25 5.25 0 0 1 7.5 16v-1.12a4.25 4.25 0 1 1 4.75-6.13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
