<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9hv67j3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-lotion" /></template>
<style>
.m9hv67j3o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 3.5v4.75H7q-1.76 0-3.005 1.245T2.75 12.5V18q0 1.76 1.245 3.005T7 22.25h2q1.76 0 3.005-1.245T13.25 18v-5.5q0-1.76-1.245-3.005T9 8.25h-.25v-4H13q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q13.074 2.75 13 2.75H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146m11.819 6.012q3.181 3.711 3.181 5.988q0 3.75-3.75 3.75t-3.75-3.75q0-2.277 3.181-5.988q.048-.056.106-.102t.124-.079t.137-.053t.144-.026t.147.003t.144.032t.135.059t.12.085q.044.037.081.081");
}

</style>
