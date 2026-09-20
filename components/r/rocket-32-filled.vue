<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="htppbsrvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rocket-32-filled" /></template>
<style>
.htppbsrvt {
  fill: currentColor;
  d: path("M9.793 26.793a1 1 0 1 1 1.414 1.414l-1.5 1.5a1 1 0 0 1-1.414-1.414zm-3-3a1 1 0 1 1 1.414 1.414l-3.5 3.5a1 1 0 0 1-1.414-1.414zM25 2a5 5 0 0 1 5 5v1.65a11.5 11.5 0 0 1-3.368 8.132l-.791.79a4.5 4.5 0 0 1-.608 5.608l-2.526 2.525a1 1 0 0 1-1.414 0l-1.814-1.814a2.5 2.5 0 0 1-3.246-.244l-.921-.921l-.864 2.59a1 1 0 0 1-1.655.39l-6.5-6.5a1 1 0 0 1 .39-1.655l2.59-.863l-.92-.92a2.5 2.5 0 0 1-.245-3.248l-1.815-1.815a1 1 0 0 1 0-1.414l2.525-2.525a4.5 4.5 0 0 1 5.609-.608l.79-.79A11.5 11.5 0 0 1 23.35 2zM3.793 20.793a1 1 0 1 1 1.414 1.414l-1.5 1.5a1 1 0 1 1-1.414-1.414zM23.35 4c-2.52 0-4.937 1-6.718 2.782l-6.864 6.865a.5.5 0 0 0 0 .707l7.878 7.878a.5.5 0 0 0 .708 0l6.864-6.864A9.5 9.5 0 0 0 28 8.65V7a3 3 0 0 0-3-3zM20.5 8a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 2a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
