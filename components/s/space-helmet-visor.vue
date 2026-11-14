<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npuha9b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:space-helmet-visor" /></template>
<style>
.npuha9b6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 20.059q-3.089-2.763-3.243-6.905t2.722-7.127T12 3.042t7.021 2.985t2.722 7.127t-3.243 6.905q-.103.092-.232.142q-.13.049-.268.049H6q-.138 0-.268-.049q-.129-.05-.232-.142M11.22 9.97l-2.25 2.25q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.25-2.25q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094");
}

</style>
