<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1voh_b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:snowboard-halfpipe" /></template>
<style>
.x1voh_b3e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.27 4.27l5.664-2.642q1.926-.897 2.824 1.028T18.73 5.48l-5.664 2.642q-1.926.897-2.824-1.028T11.27 4.27M4.75 12V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T4 7.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.25 7.926 3.25 8v4q0 3.624 2.563 6.187T12 20.75t6.187-2.563T20.75 12V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 7.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T19.25 8v4q0 3.003-2.123 5.127T12 19.25t-5.127-2.123Q4.75 15.003 4.75 12");
}

</style>
