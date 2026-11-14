<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypw5m3byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tv-wall-mounted" /></template>
<style>
.ypw5m3byw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 4v7.25h3V8.125q0-3.375 3.375-3.375h9.25q3.375 0 3.375 3.375v7.75q0 3.375-3.375 3.375h-9.25q-3.375 0-3.375-3.375V12.75h-3V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 20V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146");
}

</style>
