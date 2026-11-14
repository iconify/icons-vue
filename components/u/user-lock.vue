<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4h7mnblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-lock" /></template>
<style>
.a4h7mnblu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m13 1.5h2v-.5q0-.414-.293-.707T18.5 8.25q-1 0-1 1zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-1q0-1.768 1.25-2.286V9.25q0-2.5 2.5-2.5q1.036 0 1.768.732T21 9.25zM3.963 15.985Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>
