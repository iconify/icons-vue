<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-076acqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sunglasses" /></template>
<style>
.u-076acqv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 8.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.25 8.926 2.25 9t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T3 9.75h.167q-.417.791-.417 2q0 1.45 1.025 2.475T6.25 15.25h1q1.45 0 2.475-1.025t1.025-2.475h2.5q0 1.45 1.025 2.475t2.475 1.025h1q1.45 0 2.475-1.025t1.025-2.475q0-1.209-.417-2H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21.75 9t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 8.25m-7.424 2h-3.034q-.087-.268-.209-.5h3.538q-.171.24-.295.5");
}

</style>
