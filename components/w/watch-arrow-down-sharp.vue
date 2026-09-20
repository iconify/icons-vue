<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqwvf2bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:watch-arrow-down-sharp" /></template>
<style>
.lqwvf2bfl {
  fill: currentColor;
  d: path("M12 15.5L8.5 12l1.4-1.4l1.1 1.05V8.5h2v3.15l1.1-1.05l1.4 1.4zM9 22l-1.35-4.55q-1.2-.95-1.925-2.375T5 12t.725-3.075T7.65 6.55L9 2h6l1.35 4.55q1.2.95 1.925 2.375T19 12t-.725 3.075t-1.925 2.375L15 22zm6.538-6.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463");
}

</style>
