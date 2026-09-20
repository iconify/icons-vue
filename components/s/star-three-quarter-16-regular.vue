<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t2rkq87bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-three-quarter-16-regular" /></template>
<style>
.t2rkq87bs {
  fill: currentColor;
  d: path("M8.808 2.101a.9.9 0 0 0-1.614 0L5.673 5.183l-3.401.495a.9.9 0 0 0-.5 1.535l2.462 2.399l-.581 3.387a.9.9 0 0 0 1.306.949L8 12.348l3.042 1.6a.9.9 0 0 0 1.306-.949l-.581-3.387l2.461-2.4a.9.9 0 0 0-.499-1.534l-3.4-.495zM10 12.27V6.136a1 1 0 0 0 .133.03l3.253.472l-2.354 2.294a.9.9 0 0 0-.258.797l.555 3.24z");
}

</style>
