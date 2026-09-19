<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arkx8l6tz"/><path class="vx9-rx9zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tallahassee-police-department" /></template>
<style>
.arkx8l6tz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.633 19.034a26.2 26.2 0 0 0 5.222-5.67a73 73 0 0 0-18.69 2.74a73 73 0 0 0-17.2 7.812a26.2 26.2 0 0 0 7.46 1.94m4.508-10.918A97 97 0 0 1 19.753 4.5s2.262 1.409 4.945 5.573");
}

.vx9-rx9zb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.508 35.444a34 34 0 0 1-7.483 8.056a109 109 0 0 1-1.727-20.101q.031-1.302.104-2.572m12.644-2.406a109 109 0 0 1 11.99 17.35a58.6 58.6 0 0 1-16.8-5.12");
}

</style>
