<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9odahbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line" /></template>
<style>
.t9odahbbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 20v-4L15 5a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 1 0 2L8 20zm8-12l4 4m-8 8h12");
}

</style>
