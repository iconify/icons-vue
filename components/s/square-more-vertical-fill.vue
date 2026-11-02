<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cexeq9b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-more-vertical-fill" /></template>
<style>
.cexeq9b4k {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m7 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm.01 4H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
