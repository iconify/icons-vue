<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bi7skd6dq"/><circle class="zv2tbewos"/><path class="lzwztnbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warranty-sharp" /></template>
<style>
.bi7skd6dq {
  d: path("m11.3 2.95l-6.5 2.4l-.99.35l-.01 1.05V11c0 4.9 3.4 8.55 7.6 10.1l.6.226l.6-.226c4.2-1.55 7.6-5.2 7.6-10.1V6.75l-.01-1.05l-.99-.35l-6.5-2.4l-.7-.262z");
}

.lzwztnbnn {
  d: path("M12 9.5v1.75l1.25 1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zv2tbewos {
  cx: 12px;
  cy: 11.25px;
  r: 3.5px;
}

</style>
