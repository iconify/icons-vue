<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tjypd-ruw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:radical-thin" /></template>
<style>
.tjypd-ruw {
  fill: currentColor;
  d: path("M244 80v24a4 4 0 0 1-8 0V84H130.77l-47 125.4a4 4 0 0 1-7.49 0l-48-128a4 4 0 1 1 7.49-2.81L80 196.61l44.26-118A4 4 0 0 1 128 76h112a4 4 0 0 1 4 4");
}

</style>
