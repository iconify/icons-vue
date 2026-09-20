<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2ntmpbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-stream-outline-rounded" /></template>
<style>
.n2ntmpbcj {
  fill: currentColor;
  d: path("M19 17v-4H5v4zm0-6V7H5v4zM5 19q-.825 0-1.412-.587T3 17V7q0-.825.588-1.412T5 5h14q.825 0 1.413.588T21 7v10q0 .825-.587 1.413T19 19z");
}

</style>
