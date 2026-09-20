<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f4akwub_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slack" /></template>
<style>
.f4akwub_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.06 5.5a3.7 3.7 0 0 0 0 7.4h3.7V9.2a3.69 3.69 0 0 0-3.68-3.7m0 9.86H9.2a3.7 3.7 0 1 0 0 7.4h9.86a3.7 3.7 0 1 0 0-7.4m23.44 3.7a3.7 3.7 0 0 0-7.4 0v3.7h3.7a3.7 3.7 0 0 0 3.7-3.7m-9.86 0V9.2a3.7 3.7 0 1 0-7.4 0v9.86a3.7 3.7 0 0 0 7.4 0m-3.7 23.44a3.7 3.7 0 0 0 0-7.4h-3.7v3.7a3.7 3.7 0 0 0 3.7 3.7m0-9.86h9.86a3.7 3.7 0 1 0 0-7.4h-9.86a3.7 3.7 0 0 0 0 7.4M5.5 28.94a3.7 3.7 0 0 0 7.4 0v-3.7H9.2a3.7 3.7 0 0 0-3.7 3.7m9.86 0v9.86a3.7 3.7 0 0 0 7.4 0v-9.86a3.68 3.68 0 0 0-3.68-3.7a3.7 3.7 0 0 0-3.7 3.7");
}

</style>
