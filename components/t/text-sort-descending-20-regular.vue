<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wcj2-r_ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-sort-descending-20-regular" /></template>
<style>
.wcj2-r_ik {
  fill: currentColor;
  d: path("M4 2a.5.5 0 0 0 0 1h3.066L3.584 8.223A.5.5 0 0 0 4 9h4a.5.5 0 1 0 0-1H4.934l3.482-5.223A.5.5 0 0 0 8 2zm2.466 8.317a.5.5 0 0 0-.931 0l-2.75 7a.5.5 0 1 0 .93.366L4.378 16h3.247l.66 1.683a.5.5 0 0 0 .932-.366zM6 11.867L7.23 15H4.77zM14.5 2a.5.5 0 0 1 .5.5v13.793l2.146-2.147a.5.5 0 0 1 .708.708l-3 3a.5.5 0 0 1-.708 0l-3-3a.5.5 0 0 1 .708-.708L14 16.293V2.5a.5.5 0 0 1 .5-.5");
}

</style>
