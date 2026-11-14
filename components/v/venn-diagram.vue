<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyhtf06km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:venn-diagram" /></template>
<style>
.jyhtf06km {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.373 6.873Q1.25 8.997 1.25 12t2.123 5.127T8.5 19.25q1.932 0 3.5-.879q1.568.879 3.5.879q3.003 0 5.127-2.123T22.75 12t-2.123-5.127Q18.503 4.75 15.5 4.75q-1.932 0-3.5.879q-1.568-.879-3.5-.879q-3.003 0-5.127 2.123");
}

</style>
