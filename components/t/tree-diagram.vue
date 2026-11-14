<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5g5e_b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tree-diagram" /></template>
<style>
.q5g5e_b4l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 1.75h-2.5q-2.5 0-2.5 2.5v1.5q0 2.5 2.5 2.5h.5v3H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 12v3.75h-.5q-2.5 0-2.5 2.5v1.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768T7.25 15.75h-.5v-3h10.5v3h-.5q-2.5 0-2.5 2.5v1.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768t-1.768-.732h-.5V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 11.25h-5.25v-3h.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768T13.25 1.75");
}

</style>
