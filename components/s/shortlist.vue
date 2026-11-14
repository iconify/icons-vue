<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrgcobyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shortlist" /></template>
<style>
.nwrgcobyz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 3.25Q2.75 3.25 2.75 6T5.5 8.75T8.25 6T5.5 3.25m6.5 0Q9.25 3.25 9.25 6T12 8.75T14.75 6T12 3.25m6.5 0q-2.75 0-2.75 2.75t2.75 2.75T21.25 6T18.5 3.25M2 14q0-4.25 3.5-4.25q2.565 0 3.25 2.282Q9.435 9.75 12 9.75t3.25 2.282q.685-2.282 3.25-2.282Q22 9.75 22 14q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.5q-.138 0-.268-.049q-.129-.05-.232-.142q-.103.092-.232.142q-.13.049-.268.049h-5.5q-.138 0-.268-.049q-.129-.05-.232-.142q-.103.092-.232.142q-.13.049-.268.049h-5.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2 14.074 2 14m17.75 1.75q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732H4.25q-1.036 0-1.768-.732T1.75 19.75v-1.5q0-1.036.732-1.768t1.768-.732z");
}

</style>
