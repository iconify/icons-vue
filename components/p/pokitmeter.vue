<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ppyg-_1zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokitmeter" /></template>
<style>
.ppyg-_1zg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.7 5.7v5.9a12.86 12.86 0 0 0-3.8 23.1l3.8-3.9v11.5C.2 38.3.6 9.7 20.7 5.7m6.6 36.6v-5.9a12.86 12.86 0 0 0 3.8-23.1l-3.8 3.9V5.7c20.5 4 20.1 32.6 0 36.6");
}

</style>
