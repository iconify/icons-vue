<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cglvh5qgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tennis-scoreboard" /></template>
<style>
.cglvh5qgm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q1.76 0 3.005 1.245T22.25 6.5v7q0 1.76-1.245 3.005T18 17.75h-.25V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T16.25 21v-3.25h-8.5V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 21v-3.25H6q-1.76 0-3.005-1.245T1.75 13.5v-7q0-1.76 1.245-3.005T6 2.25m1.5 3H7q-2.5 0-2.5 2.5v4.5q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5v-4.5q0-1.036-.732-1.768T7.5 5.25m9 0q-2.5 0-2.5 2.5v4.5q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5v-4.5q0-2.5-2.5-2.5z");
}

</style>
