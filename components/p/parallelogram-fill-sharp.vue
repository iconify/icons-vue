<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrvgrvu6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parallelogram-fill-sharp" /></template>
<style>
.yrvgrvu6p {
  fill: currentColor;
  d: path("M21 2a1.002 1.002 0 0 1 .976 1.217l-4 18A1 1 0 0 1 17 22H3a1.002 1.002 0 0 1-.976-1.217l4-18A1 1 0 0 1 7 2Z");
}

</style>
