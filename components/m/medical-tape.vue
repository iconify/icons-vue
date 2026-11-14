<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqlmu78jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:medical-tape" /></template>
<style>
.wqlmu78jb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.5q0-3.417 2.416-5.834T10 3.25t5.834 2.416Q18.25 8.083 18.25 11.5t-2.416 5.834q-.513.512-1.07.916h5.986V15.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H10q-3.417 0-5.834-2.416T1.75 11.5");
}

</style>
