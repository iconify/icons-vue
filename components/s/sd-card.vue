<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p311rpbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-card" /></template>
<style>
.p311rpbhj {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8l6-6h8q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm3-11h2V7H9zm3 0h2V7h-2zm3 0h2V7h-2z");
}

</style>
