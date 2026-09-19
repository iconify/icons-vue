<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d02ese84p"/><path class="br9wd5bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:milkytracker" /></template>
<style>
.br9wd5bwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.66 20.54L24 27.47L37.34 21M24 27.47L31.09 13m6.25 8l-7.62-5.22M31.09 13v-1.8L17.44 4.5v1.9");
}

.d02ese84p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.66 20.54v16l13.3 7l13.38-7V21l-6.25-8l-13.65-6.6ZM24 43.5v-16");
}

</style>
