<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spbysvf2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:measuring-tape" /></template>
<style>
.spbysvf2i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.873 4.373Q1.75 6.497 1.75 9.5t2.123 5.127T9 16.75h7q2.907 0 3.214 3H18.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-.776q-.326-4.5-4.724-4.5h-2.573q.361-.285.7-.623Q16.25 12.503 16.25 9.5t-2.123-5.127T9 2.25T3.873 4.373M9 6.75q2.75 0 2.75 2.75T9 12.25T6.25 9.5T9 6.75");
}

</style>
