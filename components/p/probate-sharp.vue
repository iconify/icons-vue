<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kloex7bzq"/><path class="j-5_e1waq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:probate-sharp" /></template>
<style>
.j-5_e1waq {
  d: path("m8.82 12.51l2.61-2.27l.57-.49l.57.49l2.61 2.27l.57.49v5h-7.5v-5zM12 18v-2.25");
}

.kloex7bzq {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 3.5h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
