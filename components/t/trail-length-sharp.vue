<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdepe2x5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trail-length-sharp" /></template>
<style>
.hdepe2x5q {
  fill: currentColor;
  d: path("M7 17v-2h6q-.35-.425-.562-.925T12.1 13H9v-2h3.1q.125-.575.338-1.075T13 9H3V7h14q2.075 0 3.538 1.463T22 12t-1.463 3.538T17 17zm-5-4v-2h6v2zm1 4v-2h3v2z");
}

</style>
