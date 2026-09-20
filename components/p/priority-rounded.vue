<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iypzy2khj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:priority-rounded" /></template>
<style>
.iypzy2khj {
  fill: currentColor;
  d: path("M9 21q-2.5 0-4.25-1.75T3 15V9q0-2.5 1.75-4.25T9 3h6q2.5 0 4.25 1.75T21 9v6q0 2.5-1.75 4.25T15 21zm2-7.8l-1.5-1.5q-.275-.275-.7-.275t-.7.275t-.275.7t.275.7l2.2 2.2q.3.3.7.3t.7-.3l4.6-4.6q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275z");
}

</style>
