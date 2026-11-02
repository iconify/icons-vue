<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7q3t2z8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-fill" /></template>
<style>
.l7q3t2z8e {
  fill: currentColor;
  d: path("M11.796 7.891A2 2 0 0 1 10.131 11H5.869a2 2 0 0 1-1.665-3.109l2.132-3.198a2 2 0 0 1 3.328 0Zm.597 7.162a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M4 14h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2");
}

</style>
