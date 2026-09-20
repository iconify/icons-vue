<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xfb26cb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pause-bold" /></template>
<style>
.xfb26cb8g {
  fill: currentColor;
  d: path("M200 28h-40a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h40a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176h-32V52h32ZM96 28H56a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h40a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H60V52h32Z");
}

</style>
