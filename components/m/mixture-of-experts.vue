<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xybuthbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mixture-of-experts" /></template>
<style>
.xybuthbri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 1.75h.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-.5q-1.036 0-1.768-.732q-.451-.452-.624-1.018H12.75v6.25h2.011q.182-3 3.364-3h.75q3.375 0 3.375 3.375v.75q0 3.375-3.375 3.375h-.75q-3.182 0-3.364-3H12.75V19h3.067q.341-1.75 2.433-1.75h.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-.5q-1.036 0-1.768-.732q-.451-.452-.624-1.018H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-7H7.946Q7.598 15 5 15q-3 0-3-3t3-3q2.598 0 2.946 2.25h3.304v-7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q11.926 3.5 12 3.5h3.817q.341-1.75 2.433-1.75");
}

</style>
