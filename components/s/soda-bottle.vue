<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgpunijht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soda-bottle" /></template>
<style>
.tgpunijht {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75h2q2.25 0 2.25 2.25v.5q0 1.061-.5 1.621V8q0 .339.99 1.309q2.01 1.967 2.01 3.691v7q0 2.25-2.25 2.25h-7q-2.25 0-2.25-2.25v-7q0-1.724 2.01-3.691q.99-.97.99-1.309V6.121q-.5-.56-.5-1.621V4q0-2.25 2.25-2.25m2 5h-2q-.129 0-.25-.007V8q0 .97-1.441 2.381Q7.75 11.907 7.75 13v7q0 .75.75.75h7q.75 0 .75-.75v-7q0-1.093-1.559-2.619Q13.25 8.97 13.25 8V6.743q-.121.007-.25.007m-2.25 6.75q0-2 2-2t2 2t-2 2t-2-2m.25 3.25h.01q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H11q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
