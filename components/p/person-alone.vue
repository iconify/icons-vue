<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfmea_bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:person-alone" /></template>
<style>
.hfmea_bxh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 7.5Q9.5 5 12 5q1.036 0 1.768.732T14.5 7.5t-.732 1.768T12 10q-2.5 0-2.5-2.5m0 11.5h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6.25v-3q0-3.25 3.25-3.25t3.25 3.25v3h6.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T21.5 19zm.75-1.5h3.5v-3q0-1.75-1.75-1.75t-1.75 1.75z");
}

</style>
