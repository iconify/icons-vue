<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd7pmi_cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tablet-stylus" /></template>
<style>
.fd7pmi_cr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 1.75h4.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-4.25q-2.123 0-3.624-1.501T1.75 17.125V6.875q0-2.123 1.501-3.624T6.875 1.75M19.5 3.25q1.75 0 1.75 1.75v10.711q0 .433-.161.835l-.393.983q-.325.809-1.196.809t-1.196-.808l-.393-.983q-.161-.403-.161-.836V5q0-1.75 1.75-1.75M7 17.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T11 17.75z");
}

</style>
