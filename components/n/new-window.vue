<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twwyji2bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:new-window" /></template>
<style>
.twwyji2bz {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h6v2H5v14h14v-6h2v6q0 .825-.587 1.413T19 21zm11-10V8h-3V6h3V3h2v3h3v2h-3v3z");
}

</style>
