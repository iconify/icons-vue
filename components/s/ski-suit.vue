<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9s541b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-suit" /></template>
<style>
.j9s541b5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5V5a2.5 2.5 0 0 1 5 0v1.5m-5 0L5.5 8l-3 7.5H5L7.5 11v10.5h3.75L12 15l.75 6.5h3.75V11l2.5 4.5h2.5l-3-7.5l-4-1.5m-2.5 0V15");
}

</style>
