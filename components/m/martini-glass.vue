<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="embpomb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:martini-glass" /></template>
<style>
.embpomb3p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.472 3.25h9.056q1.479-.001 2.066 1.357t-.427 2.435l-4.529 4.811q-.392.417-.89.588q.002.029.002.059v7.25H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 19.75h3.25V12.5q0-.03.002-.059q-.498-.171-.89-.588L5.833 7.042q-1.014-1.077-.427-2.435q.587-1.357 2.066-1.357");
}

</style>
