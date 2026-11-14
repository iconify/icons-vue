<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szcjh9bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:test-skip" /></template>
<style>
.szcjh9bch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 19.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-15q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T19 3.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146zM9.587 6.855Q7.912 5.658 6.081 6.6T4.25 9.601v4.798q0 2.059 1.831 3.001t3.506-.255l3.359-2.399q1.413-1.009 1.413-2.746t-1.413-2.746z");
}

</style>
