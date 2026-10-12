<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bbhxfdsud"/><path class="wzkh-o-wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mosquito-sharp" /></template>
<style>
.bbhxfdsud {
  d: path("M8 11V8.5h2.5c3 0 7 2.75 10.25 6.5c-3.75 1.25-8 1.5-10.5-.25A2.5 2.5 0 0 1 8 11Zm.1-.5l-5.35 3.25");
}

.wzkh-o-wm {
  d: path("M12.5 8.85C13.25 6.5 15 5 17.5 4.5c.5 2-1 4.5-3.75 5m-3.25 3.95l-2.75 7.3m7.75-7l1.5 2.5l.25 4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
