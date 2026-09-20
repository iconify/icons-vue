<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ayt6h-b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-piece-12-regular" /></template>
<style>
.ayt6h-b4g {
  fill: currentColor;
  d: path("M6.5 1a.5.5 0 0 0-.5.5V3H4v2H2.5a.5.5 0 0 0 0 1H4v2h2v1.5a.5.5 0 0 0 1 0V8h2V7h-.5a1.5 1.5 0 1 1 0-3H9V3H7V1.5a.5.5 0 0 0-.5-.5M5 1.5a1.5 1.5 0 1 1 3 0V2h1a1 1 0 0 1 1 1v2H8.5a.5.5 0 0 0 0 1H10v2a1 1 0 0 1-1 1H8v.5a1.5 1.5 0 0 1-3 0V9H4a1 1 0 0 1-1-1V7h-.5a1.5 1.5 0 1 1 0-3H3V3a1 1 0 0 1 1-1h1z");
}

</style>
