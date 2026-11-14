<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrlv9gbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:staff-headset" /></template>
<style>
.jrlv9gbhn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.202 12.202q.475-.475 1.048-.713q.004-3.203 2.27-5.469Q8.79 3.75 12 3.75t5.48 2.27q2.266 2.266 2.27 5.469q.573.238 1.048.713q.952.952.952 2.298V16q0 1.346-.952 2.298q-.676.677-1.552.872q-.057 1.237-.948 2.128q-.952.952-2.298.952h-3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H16q.725 0 1.237-.513q.441-.44.503-1.038q-2.49-.354-2.49-3.199v-1.5q0-3.12 2.996-3.245q-.083-2.431-1.827-4.174Q14.589 5.25 12 5.25T7.581 7.081q-1.744 1.743-1.827 4.174Q8.75 11.38 8.75 14.5V16q0 3.25-3.25 3.25T2.25 16v-1.5q0-1.346.952-2.298");
}

</style>
