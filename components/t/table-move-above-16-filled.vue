<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gk-4xabsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-move-above-16-filled" /></template>
<style>
.gk-4xabsu {
  fill: currentColor;
  d: path("M2.5 2a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zM11 6h2.5a.5.5 0 0 1 .5.5V10h-3zm-9 .5a.5.5 0 0 1 .5-.5H5v4H2zM6 10V7.415q.243.085.5.085a1.5 1.5 0 1 0 3 0q.257 0 .5-.085V10zm-1 1H2v.5A2.5 2.5 0 0 0 4.5 14H5zm5 3v-3H6v3zm1.5 0H11v-3h3v.5a2.5 2.5 0 0 1-2.5 2.5M9.854 6.354a.5.5 0 0 1-.708 0L8.5 5.707V7.5a.5.5 0 0 1-1 0V5.707l-.646.647a.5.5 0 1 1-.708-.708l1.5-1.5a.5.5 0 0 1 .708 0l1.5 1.5a.5.5 0 0 1 0 .708");
}

</style>
