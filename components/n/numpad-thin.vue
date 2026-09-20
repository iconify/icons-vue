<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xf450qbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:numpad-thin" /></template>
<style>
.xf450qbhj {
  fill: currentColor;
  d: path("M76 48a12 12 0 1 1-12-12a12 12 0 0 1 12 12m52-12a12 12 0 1 0 12 12a12 12 0 0 0-12-12m64 24a12 12 0 1 0-12-12a12 12 0 0 0 12 12M64 92a12 12 0 1 0 12 12a12 12 0 0 0-12-12m64 0a12 12 0 1 0 12 12a12 12 0 0 0-12-12m64 0a12 12 0 1 0 12 12a12 12 0 0 0-12-12M64 148a12 12 0 1 0 12 12a12 12 0 0 0-12-12m64 0a12 12 0 1 0 12 12a12 12 0 0 0-12-12m0 56a12 12 0 1 0 12 12a12 12 0 0 0-12-12m64-56a12 12 0 1 0 12 12a12 12 0 0 0-12-12");
}

</style>
