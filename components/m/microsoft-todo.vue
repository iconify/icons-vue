<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nr574hhkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-todo" /></template>
<style>
.nr574hhkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.66 16.49l7.5 7.5L35.38 8.77L43 16.39L20.17 39.23L5 24.06Zm-.12 15.12l7.62-7.62");
}

</style>
