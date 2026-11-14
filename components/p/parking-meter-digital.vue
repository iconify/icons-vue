<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r765tqgsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parking-meter-digital" /></template>
<style>
.r765tqgsn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.125 1.75h-2.25q-2.123 0-3.624 1.501T5.75 6.875v2.25q0 2.123 1.501 3.624t3.624 1.501h.375v6.5H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.75v-6.5h.375q2.123 0 3.624-1.501t1.501-3.624v-2.25q0-2.123-1.501-3.624T13.125 1.75m-2.375 3h2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5t2.5-2.5");
}

</style>
