<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flfdenb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-bottom-fill" /></template>
<style>
.flfdenb4b {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm16 0a1 1 0 0 0-1-1H6a.997.997 0 0 0-1 1v8h14Z");
}

</style>
