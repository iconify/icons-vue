<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9e5honkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-true-radiant-sharp" /></template>
<style>
.w9e5honkb {
  fill: currentColor;
  d: path("M4.587 19.222q-.702-.701-.702-1.703V9.077h1v8.442q0 .597.404 1q.404.404 1 .404t1-.403t.403-1V6.48q0-1 .701-1.702q.701-.701 1.702-.701t1.703.701t.702 1.703v11.038q0 .597.404 1q.404.404 1 .404q.598 0 1-.403q.404-.404.404-1V6.48q0-1 .7-1.702q.701-.701 1.702-.701t1.703.701t.702 1.703v8.442h-1V6.481q0-.597-.403-1q-.404-.404-1.001-.404t-1 .404t-.403 1v11.038q0 1.002-.701 1.703t-1.702.701t-1.703-.701t-.702-1.703V6.481q0-.597-.404-1q-.404-.404-1-.404q-.598 0-1 .404q-.404.403-.404 1v11.038q0 1.002-.7 1.703q-.701.701-1.703.701q-1 0-1.703-.701");
}

</style>
