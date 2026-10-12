<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gqg5vxmlk"/><path class="fpn4ubbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:system-prompt-sharp" /></template>
<style>
.fpn4ubbrd {
  d: path("m6.25 7l2 1.75l-2 1.75m4 0h2M19 15l-2.75 3.5h2.5L18 21.25l3-3.5h-2.5z");
}

.gqg5vxmlk {
  d: path("M2.75 3.75h14.5v10H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
