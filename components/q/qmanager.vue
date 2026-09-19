<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb_0ybb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qmanager" /></template>
<style>
.mb_0ybb2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.62 11.15h30.76v20H8.62Zm21 24.23h9.15a4.78 4.78 0 0 0 4.78-4.79V11.65a4.78 4.78 0 0 0-4.78-4.79H9.28a4.78 4.78 0 0 0-4.78 4.79v18.94a4.78 4.78 0 0 0 4.78 4.79h9.15v2.73h-3.58v3H33v-3h-3.43Z");
}

</style>
