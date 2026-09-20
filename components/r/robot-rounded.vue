<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbq3yib5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:robot-rounded" /></template>
<style>
.dbq3yib5x {
  fill: currentColor;
  d: path("M10.066 11.066q.434-.433.434-1.066t-.434-1.066T9 8.5t-1.066.434Q7.5 9.367 7.5 10t.434 1.066T9 11.5t1.066-.434m6 0q.434-.433.434-1.066t-.434-1.066T15 8.5t-1.066.434Q13.5 9.367 13.5 10t.434 1.066T15 11.5t1.066-.434M8.5 20v-2.884q0-.27.173-.443t.443-.173H11.5V20zm4 0v-3.5h2.385q.269 0 .442.173t.173.443V20zm-6.884 0q-.672 0-1.144-.472T4 18.385V9q0-2.077 1.462-3.538T9 4h6q2.077 0 3.539 1.462T20 9v9.385q0 .67-.472 1.143q-.472.472-1.143.472H16.5v-2.884q0-.672-.472-1.144t-1.143-.472h-5.77q-.67 0-1.143.472q-.472.472-.472 1.144V20z");
}

</style>
