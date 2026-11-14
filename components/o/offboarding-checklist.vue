<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0s3kinnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:offboarding-checklist" /></template>
<style>
.i0s3kinnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-6.2m0-5.6V4q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T4 3h6q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T11 4v2.572m0 10.9V21m-9 0h10.5m2.75-15l1 1L18 4.75M20 6h1.5m-5.614 6.636l.364.364L18 10.75M20 12h1.5m-6.25 6l1 1L18 16.75M20 18h1.5M5.75 12h6.75m-2.25-2.25L12.5 12l-2.25 2.25");
}

</style>
