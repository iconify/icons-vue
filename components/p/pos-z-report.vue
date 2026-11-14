<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zryqeebqx"/><path class="pd2q_bjaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-z-report" /></template>
<style>
.pd2q_bjaz {
  d: path("M19.5 14.5a3.75 3.75 0 1 0 2.25 5a3 3 0 0 1-2.25-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zryqeebqx {
  d: path("M12.315 20.82L12 21l-3.5-2L5 21V3h14v8.5m-10.5-4h7m-7 3.5h7m-7 3.5h3");
}

</style>
