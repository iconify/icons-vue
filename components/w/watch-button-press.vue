<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uanz3qbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:watch-button-press" /></template>
<style>
.uanz3qbee {
  fill: currentColor;
  d: path("M19 12V3h2v9zM7 22l-1.35-4.55q-1.2-.95-1.925-2.375T3 12t.725-3.075T5.65 6.55L7 2h6l1.35 4.55q1.2.95 1.925 2.375T17 12t-.725 3.075t-1.925 2.375L13 22zm6.538-6.462Q15 14.075 15 12t-1.463-3.537T10 7T6.463 8.463T5 12t1.463 3.538T10 17t3.538-1.463");
}

</style>
