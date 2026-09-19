<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="frqs4sfns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplisafe" /></template>
<style>
.frqs4sfns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.21 16.71a12.21 12.21 0 0 0-24.42 0v5h24.42v9.58a12.21 12.21 0 0 1-24.42 0v-2.54");
}

</style>
