<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i20rj_bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:range-hood-outline" /></template>
<style>
.i20rj_bwr {
  fill: currentColor;
  d: path("M4.616 19q-.672 0-1.144-.472T3 17.385V13.8q0-.188.086-.368t.226-.32L8 8.423V4h8v4.423l4.521 4.521q.218.217.348.513t.131.618v3.31q0 .67-.472 1.143q-.472.472-1.143.472zm.3-6.116h14.169L15 8.8V5H9v3.8zM4.616 18h14.769q.269 0 .442-.173t.173-.442v-3.5H4v3.5q0 .269.173.442t.443.173M10 16.392v-.884h4v.884z");
}

</style>
