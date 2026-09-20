<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qn7u50bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-2-play-20-filled" /></template>
<style>
.qn7u50bsi {
  fill: currentColor;
  d: path("M15.987 3.016a1 1 0 0 0-1.285-.79l-7 2.187A1 1 0 0 0 7 5.368V13.5a2.5 2.5 0 1 0 1 2V8.368l7-2.188v2.843q.516.046 1 .184V3.18q0-.084-.013-.164M19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.263-.435l-2.994-1.65a.5.5 0 0 0-.742.437v3.3a.5.5 0 0 0 .742.438l2.994-1.65a.5.5 0 0 0 0-.875");
}

</style>
