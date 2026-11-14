<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh6gikbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:strike-zone" /></template>
<style>
.fh6gikbzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 1.75h6.5q2.5 0 2.5 2.5v6.5q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T6.25 10.75v-6.5q0-2.5 2.5-2.5m.5 5.75q0 2.75 2.75 2.75t2.75-2.75T12 4.75T9.25 7.5m11 9.25q0-2-2-2H5.75q-2 0-2 2v.295q0 1.433 1.299 2.039l6 2.8q.951.443 1.902 0l6-2.8q1.299-.606 1.299-2.039z");
}

</style>
