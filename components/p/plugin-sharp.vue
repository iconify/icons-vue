<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-78gj8wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plugin-sharp" /></template>
<style>
.x-78gj8wm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75h3.5a2 2 0 1 1 3.5 0h4v4.5a2 2 0 1 1 0 3.5v5h-13v-13zm12.75-5l.3 2.2l2.2.3l-2.2.3l-.3 2.2l-.3-2.2l-2.2-.3l2.2-.3z");
}

</style>
