<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h27tj0b0k"/><path class="j-f-pf70a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:user-feedback-score" /></template>
<style>
.h27tj0b0k {
  d: path("M4 5.5A2.5 2.5 0 0 1 6.5 3h11A2.5 2.5 0 0 1 20 5.5V14a2.5 2.5 0 0 1-2.5 2.5h-7l-4.5 4v-4a2 2 0 0 1-2-2Z");
}

.j-f-pf70a {
  d: path("m12 5l1.323 2.93l3.195.352l-2.378 2.163l.652 3.148L12 12l-2.792 1.593l.652-3.148l-2.378-2.163l3.195-.352Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
