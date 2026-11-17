<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvq9dhd5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toilet-fill-sharp" /></template>
<style>
.wvq9dhd5w {
  fill: currentColor;
  d: path("M3 10V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v7Zm17.93 2A7.02 7.02 0 0 1 15 17.93V21a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-3.082A6.01 6.01 0 0 1 3 12Z");
}

</style>
