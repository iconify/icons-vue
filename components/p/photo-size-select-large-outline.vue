<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw_bbyb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-size-select-large-outline" /></template>
<style>
.xw_bbyb9f {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V7h14v14zm0-3h10l-3.4-4.5L9 17l-1.6-2.15zM5 5H3q0-.825.588-1.412T5 3zm2 0V3h2v2zm4 0V3h2v2zm4 0V3h2v2zm4 0V3q.825 0 1.413.588T21 5zm0 14h2q0 .825-.587 1.413T19 21zm0-2v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2z");
}

</style>
