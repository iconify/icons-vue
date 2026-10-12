<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzl0fd_tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:menorah-sharp" /></template>
<style>
.tzl0fd_tf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l1.5 1.65v.95a1.5 1.5 0 0 1-3 0V4.4zM3 13V9.75M5.25 13V9.75M7.5 13V9.75M9.75 13V9.75M12 13V9m2.25 4V9.75M16.5 13V9.75M18.75 13V9.75M21 13V9.75M2.75 13h18.5M12 13v7.25m-4.25 0h8.5");
}

</style>
