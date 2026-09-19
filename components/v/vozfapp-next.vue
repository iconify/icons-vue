<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5ds1cc7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vozfapp-next" /></template>
<style>
.t5ds1cc7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.634 4.5l13.744 39l8.63-8.608l-7.458-22.636zm22.375 30.392l6.357-6.483l-1.99-5.526l-10.077-5.32");
}

</style>
