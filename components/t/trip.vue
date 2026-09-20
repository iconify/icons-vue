<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prb1g45ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trip" /></template>
<style>
.prb1g45ka {
  fill: currentColor;
  d: path("M18 21V6h2q.825 0 1.413.588T22 8v11q0 .825-.587 1.413T20 21zM10 6h4V4h-4zM8 21V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v17zm-4 0q-.825 0-1.412-.587T2 19V8q0-.825.588-1.412T4 6h2v15z");
}

</style>
