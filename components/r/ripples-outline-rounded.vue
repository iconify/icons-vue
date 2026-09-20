<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbi4e525j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ripples-outline-rounded" /></template>
<style>
.kbi4e525j {
  fill: currentColor;
  d: path("M5 19h14v-8.55q-.45.275-.962.413T17 11q-1.65 0-2.825-1.175T13 7q0-.525.138-1.038T13.55 5H5zm0 2q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM5 5v14z");
}

</style>
