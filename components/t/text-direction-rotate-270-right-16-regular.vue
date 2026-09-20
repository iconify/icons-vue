<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p56weobgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-270-right-16-regular" /></template>
<style>
.p56weobgd {
  fill: currentColor;
  d: path("M8.82 8.033a.5.5 0 0 1 .36.934L7 9.805v2.39l2.18.838a.5.5 0 0 1-.36.934l-6.5-2.5l-.069-.033a.5.5 0 0 1 .07-.9zm2.326-5.886a.5.5 0 0 1 .707 0l2 2a.5.5 0 1 1-.707.707L12 3.707V13.5a.5.5 0 1 1-1 0V3.707L9.854 4.854a.5.5 0 0 1-.708-.707zM3.893 11L6 11.81v-1.62zm1.253-8.853a.5.5 0 0 1 .708 0l2 2a.5.5 0 1 1-.708.707L6 3.707V7.5a.5.5 0 0 1-1 0V3.707L3.854 4.854a.5.5 0 0 1-.708-.707z");
}

</style>
