<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6bnv2bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potted-tree" /></template>
<style>
.u6bnv2bej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.5h12l-.75 6H6.75Zm7.161-11.581l2.864 3.501a.355.355 0 0 1-.275.58a.401.401 0 0 0-.334.624L16.5 10.25a1.447 1.447 0 0 1-1.204 2.25H8.704A1.447 1.447 0 0 1 7.5 10.25l1.084-1.626A.401.401 0 0 0 8.25 8a.355.355 0 0 1-.275-.58l2.864-3.501a1.5 1.5 0 0 1 2.322 0M12 12.5v3");
}

</style>
