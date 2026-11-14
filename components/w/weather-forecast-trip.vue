<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i15ylfjrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:weather-forecast-trip" /></template>
<style>
.i15ylfjrb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.641 16.359Q5.032 17.75 7 17.75h9.949q1.724.226 3.122-.822q1.419-1.065 1.67-2.822t-.813-3.177q-.854-1.138-2.152-1.526q-.011-2.183-1.457-3.919q-1.664-1.996-4.251-2.231T8.484 4.681q-1.743 1.453-2.143 3.61q-1.548.198-2.7 1.35Q2.25 11.032 2.25 13t1.391 3.359M19 19.75H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h14q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 19.75");
}

</style>
