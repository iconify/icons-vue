<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7owy4bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mop-outline-rounded" /></template>
<style>
.e7owy4bem {
  fill: currentColor;
  d: path("M10.692 11.5h2.616V4.192q0-.54-.384-.924q-.383-.383-.924-.383t-.924.383q-.384.384-.384.924zm-5.807 3.616h14.23v-2q0-.27-.173-.443T18.5 12.5h-13q-.27 0-.442.173q-.173.173-.173.443zm-.796 6h2.603v-2.5q0-.214.143-.357t.357-.144t.357.144t.143.356v2.5H11.5v-2.5q0-.213.143-.356t.357-.144t.357.144t.143.356v2.5h3.808v-2.5q0-.213.143-.356t.357-.144t.356.144t.144.356v2.5h2.603q.308 0 .5-.24t.097-.529l-1.231-4.23H4.723l-1.23 4.23q-.097.289.095.529t.5.24m15.978 1H3.935q-.726 0-1.19-.582q-.466-.583-.254-1.302l1.394-4.789V13q0-.633.433-1.066q.434-.434 1.067-.434h4.307V4.192q0-.961.674-1.634q.673-.673 1.634-.673t1.635.673t.673 1.634V11.5h4.307q.633 0 1.067.434q.433.433.433 1.066v2.442l1.394 4.827q.23.7-.239 1.273t-1.205.573m-.95-9.615H4.885zm-5.807-1h-2.616z");
}

</style>
