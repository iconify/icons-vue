<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="a_h5xczwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-ltr-ac-20-regular" /></template>
<style>
.a_h5xczwj {
  d: path("M9.5 2a.5.5 0 0 1 .5.5V6h1.5a.5.5 0 0 1 0 1H10v3.5a.5.5 0 0 1-1 0v-8a.5.5 0 0 1 .5-.5zM3 3.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v1.25c0 1.052-.208 2.347-.879 3.395C6.431 9.224 5.272 10 3.5 10a.5.5 0 0 1 0-1c1.428 0 2.27-.599 2.779-1.395C6.809 6.778 7 5.698 7 4.75V4H3.5a.5.5 0 0 1-.5-.5zm11.146.646a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L15.293 7H13.5a.5.5 0 0 1 0-1h1.793l-1.147-1.146a.5.5 0 0 1 0-.708zm0 8a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L15.293 15H3.5a.5.5 0 0 1 0-1h11.793l-1.147-1.146a.5.5 0 0 1 0-.708z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

</style>
