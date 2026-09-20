<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="empr1_bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reviews-outline" /></template>
<style>
.empr1_bka {
  fill: currentColor;
  d: path("M9.075 14.25L12 12.475l2.925 1.775l-.775-3.325l2.6-2.25l-3.425-.275L12 5.25L10.675 8.4l-3.425.275l2.6 2.25zM2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
