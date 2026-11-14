<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovqb0c1pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soda-can" /></template>
<style>
.ovqb0c1pa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 5.75q0-3.5 7.25-3.5t7.25 3.5V18.5q0 3.25-7.25 3.25T4.75 18.5zm9.5 0q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T13.5 5h-3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m-8 2.46V18.5q0 1.75 5.75 1.75t5.75-1.75V8.21Q15.952 9.25 12 9.25T6.25 8.21");
}

</style>
