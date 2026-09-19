<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bedqhrm4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telda" /></template>
<style>
.bedqhrm4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 19.1c0 5.412-4.388 9.8-9.8 9.8c-6.018 0-7.842-3.164-9.7-4.9s-3.682-4.9-9.7-4.9c-5.412 0-9.8 4.388-9.8 9.8");
}

</style>
