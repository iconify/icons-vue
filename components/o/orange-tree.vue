<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8jejdbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:orange-tree" /></template>
<style>
.f8jejdbtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.166 3.666Q3.75 6.083 3.75 9.5t2.416 5.834q2.147 2.146 5.084 2.386v3.03H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.75v-3.03q2.937-.24 5.084-2.386Q20.25 12.917 20.25 9.5t-2.416-5.834T12 1.25T6.166 3.666M9.5 5.5q2 0 2 2t-2 2t-2-2t2-2M13 9q0-2 2-2t2 2t-2 2t-2-2m-4 4q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
