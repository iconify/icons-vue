<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw1dxnbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-item" /></template>
<style>
.fw1dxnbbq {
  fill: currentColor;
  d: path("M20.15 13H8v-2h12.15L18.6 9.45L20 8l4 4l-4 4l-1.4-1.45zM15 9V5H5v14h10v-4h2v4q0 .825-.587 1.413T15 21H5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h10q.825 0 1.413.588T17 5v4z");
}

</style>
