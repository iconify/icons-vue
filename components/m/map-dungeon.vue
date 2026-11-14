<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp509od6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-dungeon" /></template>
<style>
.qp509od6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.789 3.946Q2.25 4.459 2.25 6.081v12.838q0 1.152.934 1.825t2.027.31l3.552-1.184q.237-.079.474 0l5.052 1.684q.711.236 1.422 0l4.5-1.5q1.539-.513 1.539-2.135V5.081q0-1.152-.934-1.825t-2.027-.31L15.237 4.13q-.237.079-.474 0L9.711 2.446q-.711-.236-1.422 0zM7.25 16.25V13.5q0-1.968 1.391-3.359T12 8.75t3.359 1.391T16.75 13.5v2.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T16 17H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
