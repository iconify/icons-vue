<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq9zav3wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smartphone-lock" /></template>
<style>
.hq9zav3wl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.625 1.75h-3.25q-2.123 0-3.624 1.501T5.25 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h3.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T13.625 1.75m-2.375 7.5V9q0-.75.75-.75t.75.75v.25zm3 .497q.139.106.268.235q.732.732.732 1.768V12q0 1.036-.732 1.768t-1.768.732h-1.5q-1.036 0-1.768-.732T8.75 12v-.25q0-1.581 1-2.162V9q0-2.25 2.25-2.25T14.25 9zm0 8.253q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.75 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
