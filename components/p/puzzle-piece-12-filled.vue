<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n--wdssdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-piece-12-filled" /></template>
<style>
.n--wdssdk {
  fill: currentColor;
  d: path("M6.5 0A1.5 1.5 0 0 0 5 1.5V2H4a1 1 0 0 0-1 1v1h-.5a1.5 1.5 0 1 0 0 3H3v1a1 1 0 0 0 1 1h1v.5a1.5 1.5 0 0 0 3 0V9h1a1 1 0 0 0 1-1V6H8.5a.5.5 0 0 1 0-1H10V3a1 1 0 0 0-1-1H8v-.5A1.5 1.5 0 0 0 6.5 0");
}

</style>
