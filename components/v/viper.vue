<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_2lkdd9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:viper" /></template>
<style>
.s_2lkdd9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.22 42.26L5.5 5.74h13.9l9.15 17.85l8.38-17.75h5.57Zm4.33-18.67l2.55 4.96");
}

</style>
