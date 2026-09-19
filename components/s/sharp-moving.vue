<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiyh22bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-moving" /></template>
<style>
.jiyh22bzy {
  fill: currentColor;
  d: path("M19.71 9.71L22 12V6h-6l2.29 2.29l-4.17 4.17a.996.996 0 0 1-1.41 0l-1.17-1.17a3 3 0 0 0-4.24 0L2 16.59L3.41 18l5.29-5.29a.996.996 0 0 1 1.41 0l1.17 1.17a3 3 0 0 0 4.24 0z");
}

</style>
