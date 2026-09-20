<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jzon044ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-32-regular" /></template>
<style>
.jzon044ni {
  fill: currentColor;
  d: path("M10 18a2 2 0 1 0 0-4a2 2 0 0 0 0 4m6 0a2 2 0 1 0 0-4a2 2 0 0 0 0 4m8-2a2 2 0 1 1-4 0a2 2 0 0 1 4 0m6 0c0 7.732-6.268 14-14 14S2 23.732 2 16S8.268 2 16 2s14 6.268 14 14m-2 0c0-6.627-5.373-12-12-12S4 9.373 4 16s5.373 12 12 12s12-5.373 12-12");
}

</style>
