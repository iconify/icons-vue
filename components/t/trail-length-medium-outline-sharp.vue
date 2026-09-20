<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiurajbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trail-length-medium-outline-sharp" /></template>
<style>
.aiurajbxq {
  fill: currentColor;
  d: path("M7 17v-2h5q-.35-.425-.562-.925T11.1 13H5v-2h6.1q.125-.575.338-1.075T12 9H7V7h9q2.075 0 3.538 1.463T21 12t-1.463 3.538T16 17zm9-2q1.25 0 2.125-.875T19 12t-.875-2.125T16 9t-2.125.875T13 12t.875 2.125T16 15M3 17v-2h3v2zm13-5");
}

</style>
