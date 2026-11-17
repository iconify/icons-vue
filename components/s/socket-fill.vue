<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1s9irbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:socket-fill" /></template>
<style>
.a1s9irbnr {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm10 12a5 5 0 1 0-.001-10.001A5 5 0 0 0 12 17m-4-5a1.5 1.5 0 1 1 3.001.001A1.5 1.5 0 0 1 8 12m5 0a1.5 1.5 0 1 1 3.001.001A1.5 1.5 0 0 1 13 12");
}

</style>
