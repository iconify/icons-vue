<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwnrbqbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toilet-fill" /></template>
<style>
.zwnrbqbnp {
  fill: currentColor;
  d: path("M3 10V5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v5Zm17.93 2A7.02 7.02 0 0 1 15 17.93V19a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3v-1.082A6.01 6.01 0 0 1 3 12Z");
}

</style>
