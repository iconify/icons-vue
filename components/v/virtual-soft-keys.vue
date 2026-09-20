<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8kqh55kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:virtual-soft-keys" /></template>
<style>
.m8kqh55kf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.53 19.197v9.607L4.5 24zM28.145 24c0 2.475-1.934 4.481-4.32 4.481c-2.385 0-4.32-2.006-4.32-4.481s1.935-4.481 4.32-4.481s4.32 2.006 4.32 4.481m7.553-4.047H43.5v8.093h-7.802z");
}

</style>
