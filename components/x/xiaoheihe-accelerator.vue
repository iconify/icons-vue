<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lm69f68vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xiaoheihe-accelerator" /></template>
<style>
.lm69f68vr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.418 5.5L8.185 29.191H21.1l1.55-2.495M20.582 42.5l19.233-23.691H26.9l-1.55 2.495");
}

</style>
