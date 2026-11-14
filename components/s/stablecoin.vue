<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozdqtgbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stablecoin" /></template>
<style>
.ozdqtgbhk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 9q0-3.25 4.75-3.25T11.25 9v3q0 3.25-4.75 3.25T1.75 12zm11 0q0-3.25 4.75-3.25T22.25 9v3q0 3.25-4.75 3.25T12.75 12zm-9.5 2.626V12q0 1.75 3.25 1.75T9.75 12v-.374q-1.169.624-3.25.624t-3.25-.624m11 0V12q0 1.75 3.25 1.75T20.75 12v-.374q-1.169.624-3.25.624t-3.25-.624M2.5 16.75h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
