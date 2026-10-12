<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vzpqhv5qj"/><circle class="tyhetpb4e"/><path class="jx412ibya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packet-sniff-sharp" /></template>
<style>
.jx412ibya {
  d: path("M10 6.75c-.6-.9.6-1.85 0-2.75m4 2.75c-.6-.9.6-1.85 0-2.75");
}

.tyhetpb4e {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

.vzpqhv5qj {
  d: path("M2.75 9.25h5.5v5.5h-5.5zm13 0h5.5v5.5h-5.5zM8.25 12h7.5M12 12v4.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
