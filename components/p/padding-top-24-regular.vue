<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgvkosbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:padding-top-24-regular" /></template>
<style>
.lgvkosbuz {
  fill: currentColor;
  d: path("M4.5 2.75A.75.75 0 0 1 5.25 2h.867a.75.75 0 0 1 0 1.5H5.25a.75.75 0 0 1-.75-.75m3.467 0a.75.75 0 0 1 .75-.75h1.733a.75.75 0 0 1 0 1.5H8.717a.75.75 0 0 1-.75-.75m4.333 0a.75.75 0 0 1 .75-.75h1.733a.75.75 0 0 1 0 1.5H13.05a.75.75 0 0 1-.75-.75m4.333 0a.75.75 0 0 1 .75-.75h.867a.75.75 0 0 1 0 1.5h-.867a.75.75 0 0 1-.75-.75M4.5 21.25a.75.75 0 0 1 .75-.75h13a.75.75 0 0 1 0 1.5h-13a.75.75 0 0 1-.75-.75m7.78-16.03a.75.75 0 0 0-1.06 0l-5 5a.75.75 0 1 0 1.06 1.06L11 7.56v10.69a.75.75 0 0 0 1.5 0V7.56l3.72 3.72a.75.75 0 1 0 1.06-1.06z");
}

</style>
