<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pq01k2byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-warning-32-filled" /></template>
<style>
.pq01k2byf {
  fill: currentColor;
  d: path("m2.515 11.875l13.011 7.006a1 1 0 0 0 .948 0l7.208-3.88h5.82q.259-.001.498-.05v7.55a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 22.5V11.588zm14.755-.507c-.83 1.656.356 3.607 2.194 3.63L16 16.866L3.48 10.124l-1.476-.82A4.5 4.5 0 0 1 6.5 5h13.959zm5.894-9.54c.553-1.104 2.12-1.104 2.672 0l5.002 9.992c.5 1-.222 2.18-1.336 2.18H19.498c-1.114 0-1.837-1.18-1.336-2.18zM24.5 11a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-7a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5");
}

</style>
