<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sxyvmebpf"/><path class="qtyz7ml3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tab-bar-sharp" /></template>
<style>
.qtyz7ml3f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 17.5h.01m4.49 0h.01m4.49 0h.01");
}

.sxyvmebpf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm.75 11h17");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
