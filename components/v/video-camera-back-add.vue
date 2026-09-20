<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkbcc8rop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-camera-back-add" /></template>
<style>
.qkbcc8rop {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18v-7q.65.5 1.425.75T5 12q2.075 0 3.538-1.463T10 7q0-.8-.25-1.575T9 4h7q.825 0 1.413.588T18 6v4.5l4-4v11l-4-4V18q0 .825-.587 1.413T16 20zm0-10V8H2V6h2V4h2v2h2v2H6v2zm1 6h10l-3.375-4.5L9 15l-1.625-2.175z");
}

</style>
