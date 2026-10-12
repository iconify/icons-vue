<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dedomujev"/><path class="gq64eebob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:t-shirt-edit-sharp" /></template>
<style>
.dedomujev {
  d: path("M7.87 3.73L3.63 6.02l-.88.48l.4.92l.95 2.16l.4.92l.94-.35l.12-.05l.94-.35v11h11v-11l.94.35l.12.05l.94.35l.4-.92l.95-2.16l.4-.92l-.88-.48l-4.24-2.29l-.88-.48h-6.5z");
}

.gq64eebob {
  d: path("M9.25 3.5a2.75 2.5 0 0 0 5.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
