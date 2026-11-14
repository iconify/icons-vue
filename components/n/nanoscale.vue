<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-o3-ib0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nanoscale" /></template>
<style>
.g-o3-ib0a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.75q-.001-2.9 2.049-4.951Q5.85 3.748 8.75 3.748t4.951 2.051t2.049 4.951q.001 2.9-2.049 4.951q-2.051 2.051-4.951 2.051t-4.951-2.051T1.75 10.75m17.75 2q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5m2 6.25h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21.5 19");
}

</style>
