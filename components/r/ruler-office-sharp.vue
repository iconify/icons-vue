<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdjno3b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ruler-office-sharp" /></template>
<style>
.jdjno3b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h18.5v6H2.75zm3.25 0v2.5m3-2.5v1.5m3-1.5v2.5m3-2.5v1.5m3-1.5v2.5M7.75 5h13.5v4H7l-.66-.35l-2.43-1.3L3.25 7l.66-.35l2.43-1.3L7 5zM8 5v4");
}

</style>
