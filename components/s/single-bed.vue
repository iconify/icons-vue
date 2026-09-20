<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzomhool"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:single-bed" /></template>
<style>
.wfzomhool {
  fill: currentColor;
  d: path("M7 19H6l-.65-2H4v-5.025q0-.825.588-1.4T6 10V7q0-.825.588-1.412T8 5h8q.825 0 1.413.588T18 7v3q.825 0 1.413.588T20 12v5h-1.35L18 19h-1l-.65-2h-8.7zm6-9h3V7h-3zm-5 0h3V7H8z");
}

</style>
