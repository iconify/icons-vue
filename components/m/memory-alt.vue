<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9v_ssbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:memory-alt" /></template>
<style>
.z9v_ssbqd {
  fill: currentColor;
  d: path("M6 15h2V9H6zm5 0h2V9h-2zm5 0h2V9h-2zM5 21v-2H4q-.825 0-1.412-.587T2 17V7q0-.825.588-1.412T4 5h1V3h2v2h4V3h2v2h4V3h2v2h1q.825 0 1.413.588T22 7v10q0 .825-.587 1.413T20 19h-1v2h-2v-2h-4v2h-2v-2H7v2z");
}

</style>
