<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s4663rbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:strafe" /></template>
<style>
.s4663rbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.308 32.808L3.5 24l8.808-8.808m20.5 20.5L24 44.5l-8.808-8.808m0-23.384L24 3.5l8.808 8.808m2.884 2.884L44.5 24l-8.808 8.808");
}

</style>
