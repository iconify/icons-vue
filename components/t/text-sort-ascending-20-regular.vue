<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="omlh0qbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-sort-ascending-20-regular" /></template>
<style>
.omlh0qbqp {
  fill: currentColor;
  d: path("M6.466 2.317a.5.5 0 0 0-.931 0l-2.75 7a.5.5 0 0 0 .93.366L4.378 8h3.247l.66 1.683a.5.5 0 0 0 .932-.366zM6 3.867L7.23 7H4.77zM4 11a.5.5 0 0 0 0 1h3.066l-3.482 5.223A.5.5 0 0 0 4 18h4a.5.5 0 0 0 0-1H4.934l3.482-5.223A.5.5 0 0 0 8 11zm10.5-9a.5.5 0 0 1 .5.5v13.793l2.146-2.147a.5.5 0 0 1 .708.708l-3 3a.5.5 0 0 1-.708 0l-3-3a.5.5 0 0 1 .708-.708L14 16.293V2.5a.5.5 0 0 1 .5-.5");
}

</style>
