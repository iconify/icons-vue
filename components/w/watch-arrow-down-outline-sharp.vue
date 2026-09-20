<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uge51jbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:watch-arrow-down-outline-sharp" /></template>
<style>
.uge51jbwy {
  fill: currentColor;
  d: path("M12 15.5L8.5 12l1.4-1.4l1.1 1.05V8.5h2v3.15l1.1-1.05l1.4 1.4zM10.5 4h3zm0 16h3zM9 22l-1.35-4.55q-1.2-.95-1.925-2.375T5 12t.725-3.075T7.65 6.55L9 2h6l1.35 4.55q1.2.95 1.925 2.375T19 12t-.725 3.075t-1.925 2.375L15 22zm6.538-6.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463M10.1 5.25q.5-.125.963-.2T12 4.975t.938.075t.962.2L13.5 4h-3zM10.5 20h3l.4-1.25q-.5.125-.962.188T12 19t-.937-.062t-.963-.188z");
}

</style>
