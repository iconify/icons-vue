<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b52_hpb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:person-dress" /></template>
<style>
.b52_hpb4b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5q-2.75 0-2.75 2.75T12 7t2.75-2.75T12 1.5m.713 5.75q1.838-.001 2.387 1.754l1.406 4.5q.377 1.208-.372 2.227q-.71.966-1.884 1.016V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T12.75 21v-4.25h-1.5V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.75 21v-4.253q-1.174-.05-1.884-1.016q-.749-1.019-.372-2.227l1.406-4.5q.549-1.755 2.387-1.754z");
}

</style>
