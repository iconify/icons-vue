<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzusa9tjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:watch-button-press-outline" /></template>
<style>
.nzusa9tjr {
  fill: currentColor;
  d: path("M19 12V3h2v9zM7 22l-1.35-4.55q-1.2-.95-1.925-2.375T3 12t.725-3.075T5.65 6.55L7 2h6l1.35 4.55q1.2.95 1.925 2.375T17 12t-.725 3.075t-1.925 2.375L13 22zm6.538-6.462Q15 14.075 15 12t-1.463-3.537T10 7T6.463 8.463T5 12t1.463 3.538T10 17t3.538-1.463M8.5 4h3zm0 16h3zM8.1 5.25q.5-.125.963-.2T10 4.975t.938.075t.962.2L11.5 4h-3zM8.5 20h3l.4-1.25q-.5.125-.962.188T10 19t-.937-.062t-.963-.188z");
}

</style>
