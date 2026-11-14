<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvabs2xrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:printer-3d-bed" /></template>
<style>
.qvabs2xrl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.211 12.073l2.133-4Q6.05 6.75 7.55 6.75H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 6.75h4.45q1.5 0 2.206 1.323l2.133 4q.658 1.233-.044 2.432q1.505.62 1.505 2.745q0 3-3 3H4.75q-1.243 0-2.121-.879q-.879-.878-.879-2.121t.879-2.121q.319-.32.687-.523l-.043-.07q-.728-1.214-.062-2.463");
}

</style>
