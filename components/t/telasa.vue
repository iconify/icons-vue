<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q42u79b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telasa" /></template>
<style>
.q42u79b_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 27.128a11 11 0 0 1 10.395 7.401L24 4.5L13.605 34.53A11 11 0 0 1 24 27.127M10.5 43.5l1.553-4.486m23.894 0L37.5 43.5");
}

</style>
