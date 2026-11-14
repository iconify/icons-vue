<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1d7s4bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mode-program" /></template>
<style>
.o1d7s4bve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.487 1.75h1.026q.844.002 1.166.78t-.273 1.374q-.583.584-1.406.584t-1.406-.583Q10 3.308 10.321 2.53q.322-.778 1.164-.78zM6.166 8.166Q3.75 10.583 3.75 14t2.416 5.834T12 22.25t5.834-2.416Q20.25 17.417 20.25 14t-2.416-5.834T12 5.75T6.166 8.166M10.5 15.75V18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9 18v-7.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.5q3 0 3 3t-3 3zm0-1.5h1.75q1.5 0 1.5-1.5t-1.5-1.5H10.5z");
}

</style>
