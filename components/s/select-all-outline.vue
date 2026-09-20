<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c56hv84rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:select-all-outline" /></template>
<style>
.c56hv84rx {
  fill: currentColor;
  d: path("M7 17V7h10v10zm2-2h6V9H9zm-4 4v2q-.825 0-1.412-.587T3 19zm-2-2v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm2-4H3q0-.825.588-1.412T5 3zm2 16v-2h2v2zM7 5V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2q0 .825-.587 1.413T19 21m0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3q.825 0 1.413.588T21 5z");
}

</style>
