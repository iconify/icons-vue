<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kggskhbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:navigation-end" /></template>
<style>
.kggskhbfp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 7.75q-2.25 0-2.25 2.25V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.063 0 .125.011t.122.031t.115.051t.104.07q.05.039.092.086t.076.1t.058.112t.039.119q.344-.08.769-.08h5Q8.75 2.75 8.75 5v2q0 .475.1.85q-.375-.1-.85-.1zM10.25 10q0-.475-.1-.85q.375.1.85.1h2q.475 0 .85-.1q-.1.375-.1.85v2q0 2.25 2.25 2.25H8q2.25 0 2.25-2.25zm10 0V5q0-2.25-2.25-2.25h-5q2.25 0 2.25 2.25v2q0 .475-.1.85q.375-.1.85-.1h2q2.25 0 2.25 2.25m-15 4.174V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 21v-9q0 1.837 1.5 2.174");
}

</style>
