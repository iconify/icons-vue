<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p488hebtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shell-casing" /></template>
<style>
.p488hebtc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 18.286V9.5q0-.208.107-.386L9.75 6.792V4.5q0-.208.107-.386Q10.825 2.5 12 2.5t2.143 1.614q.107.178.107.386v2.292l1.393 2.322q.107.178.107.386v8.786q1.5.232 1.5 1.964q0 2-2 2h-6.5q-2 0-2-2q0-1.732 1.5-1.964M14.25 7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.75 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T14.25 7");
}

</style>
