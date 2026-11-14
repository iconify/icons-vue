<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2p_gzbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:progress-100" /></template>
<style>
.b2p_gzbyi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 7.25h-11q-1.968 0-3.359 1.391T1.75 12t1.391 3.359T6.5 16.75h11q1.968 0 3.359-1.391T22.25 12t-1.391-3.359T17.5 7.25M4.202 9.702Q5.154 8.75 6.5 8.75h11q3.25 0 3.25 3.25t-3.25 3.25h-11q-3.25 0-3.25-3.25q0-1.346.952-2.298M18.5 11.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
