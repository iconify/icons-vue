<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjvgufb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:marker-diamond" /></template>
<style>
.qjvgufb3w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.142 9.461l-5.268-5.97q-.746-.846-1.874-.846t-1.874.846l-5.269 5.97q-1.314 1.491-.158 3.107l5.267 7.374q.748 1.047 2.034 1.047t2.034-1.047l5.267-7.374q1.156-1.616-.159-3.107M8.5 11q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5T8.5 11");
}

</style>
