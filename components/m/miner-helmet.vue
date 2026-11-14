<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9_-j8dwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:miner-helmet" /></template>
<style>
.q9_-j8dwd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 16.25V15q0-3.624 2.563-6.187T12 6.25t6.187 2.563T20.75 15v1.25h.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 17t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm16 0V15q0-3.003-2.123-5.127T12 7.75T6.873 9.873T4.75 15v1.25zM9.25 12q0-2.75 2.75-2.75T14.75 12T12 14.75T9.25 12");
}

</style>
