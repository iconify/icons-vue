<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsbovyoqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-rain-24-filled" /></template>
<style>
.vsbovyoqr {
  fill: currentColor;
  d: path("M12 4.001c3.169 0 4.966 2.097 5.227 4.63h.08A3.687 3.687 0 0 1 21 12.314a3.687 3.687 0 0 1-3.692 3.682h-.582l-1.583 2.637a.75.75 0 0 1-1.344-.659l.045-.091l1.15-1.887h-2.136l-1.583 2.637a.75.75 0 0 1-1.344-.659l.045-.091l1.15-1.887H8.987l-1.581 2.637a.75.75 0 0 1-1.344-.659l.045-.091l1.148-1.887h-.562A3.687 3.687 0 0 1 3 12.314A3.687 3.687 0 0 1 6.693 8.63h.08C7.035 6.08 8.831 4 12 4");
}

</style>
