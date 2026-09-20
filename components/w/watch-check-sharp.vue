<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyp97u66p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:watch-check-sharp" /></template>
<style>
.yyp97u66p {
  fill: currentColor;
  d: path("M10.95 15.175L8.1 12.35l1.425-1.4l1.425 1.4l3.525-3.525l1.425 1.4zM9 22l-1.35-4.55q-1.2-.95-1.925-2.375T5 12t.725-3.075T7.65 6.55L9 2h6l1.35 4.55q1.2.95 1.925 2.375T19 12t-.725 3.075t-1.925 2.375L15 22zm6.538-6.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463");
}

</style>
