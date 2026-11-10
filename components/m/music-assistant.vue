<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qs30ngb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-assistant" /></template>
<style>
.qs30ngb3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.855 41.356h33.937q1.506-.15 1.708-1.602V25.599c-.121-1.75-.245-2.306-1.464-3.553L24.954 5.59c-.677-.482-1.323-.483-2.078.136l-16.1 15.932c-.72.724-1.192 1.433-1.276 2.824v15.32c.006.575.283 1.409 1.355 1.555m2.957-17.352V37.34m5.398-13.335V37.34m5.3-13.335V37.34m4.642 0l4.411-13.335m3.687 0l4.378 13.335");
}

</style>
