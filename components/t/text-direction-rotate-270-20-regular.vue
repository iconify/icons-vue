<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="e2xvferhd"/><path class="bl74v3bgm"/><path class="p0oowpb-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-270-20-regular" /></template>
<style>
.bl74v3bgm {
  d: path("M16.854 5.146a.5.5 0 1 1-.707.708L15 4.707V16.5a.5.5 0 0 1-1 0V4.707l-1.146 1.147a.5.5 0 1 1-.707-.708l2-2a.5.5 0 0 1 .707 0l2 2z");
  fill: currentColor;
}

.e2xvferhd {
  d: path("M8.854 5.146a.5.5 0 1 1-.707.708L7 4.707V9.5a.5.5 0 0 1-1 0V4.707L4.854 5.854a.5.5 0 1 1-.707-.708l2-2a.5.5 0 0 1 .707 0l2 2z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.p0oowpb-a {
  d: path("M3 13.5a.5.5 0 0 1 .324-.468l8-3a.5.5 0 0 1 .352.936L9 11.972v3.057l2.676 1.003a.5.5 0 0 1-.352.936l-8-3A.5.5 0 0 1 3 13.5zm1.924 0L8 14.654v-2.307L4.924 13.5z");
  fill: currentColor;
}

</style>
