<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mqfkbmbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minimalist-phone" /></template>
<style>
.mqfkbmbwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5zc11.874 0 21.5 9.626 21.5 21.5S35.874 45.5 24 45.5S2.5 35.874 2.5 24A21.43 21.43 0 0 1 8.797 8.797");
}

</style>
