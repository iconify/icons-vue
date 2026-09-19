<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8hkm7bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wdbible" /></template>
<style>
.z8hkm7bfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 17.9c-5.44 7.36-12.9 14.71-22.09 14.71c-6.53 0-12.24-4.11-16.91-8.61c4.67-4.5 10.38-8.61 16.91-8.61c9.19 0 16.65 7.35 22.09 14.71");
}

</style>
