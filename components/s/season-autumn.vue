<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2m7hactn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:season-autumn" /></template>
<style>
.y2m7hactn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.908 3.77q7.342.334 7.342 6.23q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.25V12q0 6.625-5.864 10.143q-.088.053-.186.08t-.2.027t-.2-.027t-.186-.08Q5.75 18.625 5.75 12v-1.25H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.75 10.074 3.75 10q0-5.982 7.558-6.239Q11.648 1.75 14 1.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014q-.806 0-1.092.52m3.842 6.98V12q0 5.554-4.75 8.617Q7.25 17.554 7.25 12v-1.25z");
}

</style>
