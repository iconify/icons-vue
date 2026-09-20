<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juo2qollc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-check-rounded" /></template>
<style>
.juo2qollc {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm4.05-10.8l-.7-.7q-.275-.275-.7-.275t-.7.275t-.275.7t.275.7l1.4 1.4q.3.3.7.3t.7-.3l3.55-3.55q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275z");
}

</style>
