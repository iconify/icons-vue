<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooy5oebwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:power-cut-candle" /></template>
<style>
.ooy5oebwv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.53 1.97q2.72 2.719 2.72 4.53q0 3.25-3.25 3.25T8.75 6.5q0-1.811 2.72-4.53q.105-.106.243-.163T12 1.75t.287.057t.243.163m2.488 9.512q-.732-.732-1.768-.732h-2.5q-2.5 0-2.5 2.5v4q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-4q0-1.036-.732-1.768M19 20.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 20.75z");
}

</style>
