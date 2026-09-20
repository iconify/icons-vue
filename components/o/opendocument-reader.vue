<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yh9ve7avf"/><path class="va0lvvb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opendocument-reader" /></template>
<style>
.va0lvvb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.396 29.901V22h1.284a3.96 3.96 0 0 1 3.95 3.95a3.96 3.96 0 0 1-3.95 3.951Zm-7.268-2.568a2.618 2.618 0 1 0 5.235 0v-2.666A2.656 2.656 0 0 0 16.696 22a2.574 2.574 0 0 0-2.568 2.667Zm14.509 2.568V22h2.568a2.667 2.667 0 1 1 0 5.333h-2.568m2.756-.006l2.479 2.574");
}

.yh9ve7avf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2Zm-11-11l11 11");
}

</style>
