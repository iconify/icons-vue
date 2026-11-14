<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufu12xi4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:operating-table" /></template>
<style>
.ufu12xi4y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 6.75H4.25q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h5.076q-.076.337-.076.75V17q0 .413.076.75H7.5q-2.25 0-2.25 2.25t2.25 2.25h9q2.25 0 2.25-2.25t-2.25-2.25h-1.871q.121-.35.121-.75v-4.5q0-.4-.121-.75h5.121q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V11q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T8 11.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 11V7.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 6.75");
}

</style>
