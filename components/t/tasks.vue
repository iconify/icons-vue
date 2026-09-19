<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_9o_r4uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tasks" /></template>
<style>
.y_9o_r4uv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.13 7.85l6.66 4.87l-16.37 22.39l-4.87 6.67l-6.66-4.87l-11.1-8.12l4.87-6.66l11.1 8.12Z");
}

</style>
