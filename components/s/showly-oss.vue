<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvvvvlb-u"/><path class="v3i3q32ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:showly-oss" /></template>
<style>
.v3i3q32ia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.771 32.003c1.226 1.596 2.764 2.191 4.904 2.191h2.96a4.99 4.99 0 0 0 4.99-4.989v-.021a4.99 4.99 0 0 0-4.99-4.99H22.37a4.995 4.995 0 0 1-4.995-4.994h0a5.005 5.005 0 0 1 5.005-5.006h2.945c2.14 0 3.678.595 4.904 2.192");
}

.wvvvvlb-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.745h39v24.897h-39zm4.788 27.51h29.424");
}

</style>
