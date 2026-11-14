<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5nkaeb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:statement-request" /></template>
<style>
.m5nkaeb3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.702 2.702Q1.75 3.654 1.75 5v10q0 3.25 3.25 3.25h.75V21q0 .125.041.243q.04.119.117.217q.045.059.101.107t.12.085q.064.036.135.06q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.053q.066-.033.124-.078l4.297-3.342H19q3.25 0 3.25-3.25V5q0-1.346-.952-2.298T19 1.75H5q-1.346 0-2.298.952M9.75 4.75h4.5q2.5 0 2.5 2.5v5.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 12.75v-5.5q0-2.5 2.5-2.5");
}

</style>
