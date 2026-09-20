<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v95l0tomh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-card-outline" /></template>
<style>
.v95l0tomh {
  fill: currentColor;
  d: path("M9 11h2V7H9zm3 0h2V7h-2zm3 0h2V7h-2zM6 22q-.825 0-1.412-.587T4 20V8l6-6h8q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm0-2h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>
