<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk0-ovwrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-arrow-down-sharp" /></template>
<style>
.tk0-ovwrc {
  fill: currentColor;
  d: path("M3.188 17.813Q1 15.625 1 12.5t2.188-5.312T8.5 5q1.3 0 2.45.413t2.1 1.137L14.1 5.5l1.4 1.4l-1.05 1.05q.725.95 1.138 2.113T16 12.5q0 3.125-2.187 5.313T8.5 20t-5.312-2.187M19.5 20L16 16.5l1.4-1.4l1.1 1.1V4h2v12.175l1.075-1.075L23 16.5zM6 4V2h5v2zm1.5 9.5h2v-5h-2z");
}

</style>
