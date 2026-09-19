<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uq0el665a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:make-by-kbank" /></template>
<style>
.uq0el665a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.5 29.5v-3.75c0-6.075-4.925-11-11-11s-11 4.925-11 11v7.5m22-7.5a8.5 8.5 0 0 1 17 0v7.5");
}

</style>
