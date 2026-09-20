<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk47f8b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transit-enterexit-rounded" /></template>
<style>
.dk47f8b-v {
  fill: currentColor;
  d: path("M11.15 15h3.35q.625 0 1.063.438T16 16.5t-.437 1.063T14.5 18H7q-.425 0-.712-.288T6 17V9.5q0-.625.438-1.062T7.5 8t1.063.438T9 9.5v3.25l5.7-5.7q.45-.45 1.1-.45t1.1.45t.45 1.1t-.45 1.1z");
}

</style>
