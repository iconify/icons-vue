<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l18aotp8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-off-16-regular" /></template>
<style>
.l18aotp8i {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .707 0l13 13a.5.5 0 1 1-.707.707L9.293 10h-.988L6.97 13.67a.501.501 0 0 1-.931.022L5.334 12H2.668l-.706 1.692a.502.502 0 0 1-.923-.384l2.5-6a.501.501 0 0 1 .923 0l2.006 4.815l1.319-3.629l-6.64-6.64a.5.5 0 0 1 0-.708M10.501 2a.5.5 0 0 1 .47.33l3.725 10.245l-1.672-1.672l-.328-.903h-.575l-1-1h1.212L10.5 3.962l-1.18 3.24l-.78-.781l1.49-4.092l.032-.071A.5.5 0 0 1 10.501 2m-7.416 9h1.832L4 8.8z");
}

</style>
