<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfec-dg6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-inbox" /></template>
<style>
.hfec-dg6n {
  fill: currentColor;
  d: path("M7 17q-.825 0-1.412-.587T5 15V5q0-.825.588-1.412T7 3h14q.825 0 1.413.588T23 5v10q0 .825-.587 1.413T21 17zm7-5q.825 0 1.413-.587T16 10h5V5H7v5h5q0 .825.588 1.413T14 12m5 9H3q-.825 0-1.412-.587T1 19V7h2v12h16z");
}

</style>
