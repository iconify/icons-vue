<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6g5o-b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-camera-back-add-outline" /></template>
<style>
.q6g5o-b9v {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18v-6h2v6h12V6h-6V4h6q.825 0 1.413.588T18 6v4.5l4-4v11l-4-4V18q0 .825-.587 1.413T16 20zm1-4h10l-3.375-4.5L9 15l-1.625-2.175zm-1-6V8H2V6h2V4h2v2h2v2H6v2z");
}

</style>
