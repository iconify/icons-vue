<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1rt_-5ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:navigation-start" /></template>
<style>
.y1rt_-5ee {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 20V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q3.574 3.25 3.5 3.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 3.926 2.75 4v16q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.25 20m7.722-14.472h.001l5.577 3.647q1.528.999 1.528 2.825t-1.528 2.825l-5.578 3.647q-1.683 1.101-3.453.144T6.75 15.647V8.353q0-2.012 1.769-2.969q1.77-.957 3.453.144");
}

</style>
