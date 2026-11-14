<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvgmev37e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:terminus-symbol" /></template>
<style>
.bvgmev37e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 1.75h-2q-1.76 0-3.005 1.245T6.75 6v8q0 1.76 1.245 3.005T11 18.25h2q1.76 0 3.005-1.245T17.25 14V6q0-1.76-1.245-3.005T13 1.75m-7 18h12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 19.75");
}

</style>
