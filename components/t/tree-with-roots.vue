<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vomtxjbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-with-roots" /></template>
<style>
.vomtxjbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.161 3.919l2.864 3.501a.355.355 0 0 1-.275.58a.412.412 0 0 0-.347.633l1.63 2.562a1.5 1.5 0 0 1-1.266 2.305H8.233a1.5 1.5 0 0 1-1.266-2.305l1.63-2.562A.412.412 0 0 0 8.25 8a.355.355 0 0 1-.275-.58l2.864-3.501a1.5 1.5 0 0 1 2.322 0M12 13.5v8m0-4.5c-1.5.5-5 2.5-7 4.5m7-4.5c1.5.5 5 2.5 7 4.5");
}

</style>
