<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vgh0jfbzr"/><path class="cs4w9bzmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monobloc" /></template>
<style>
.cs4w9bzmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.897 13.998v19.5l17.077 9.75l17.077-9.75v-19.5m-17.077 29.25v-19.5");
}

.vgh0jfbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.051 13.998l-17.077-9.75l-17.077 9.75l17.077 9.75z");
}

</style>
