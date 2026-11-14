<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl6l_gb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:printer-3d-nozzle" /></template>
<style>
.wl6l_gb-z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.125 1.75h3.75q3.375 0 3.375 3.375v.25q0 3.375-3.375 3.375h-.711q1.228 0 1.892 1.035t.152 2.153l-1.464 3.193Q13.231 16.249 12 16.25q-1.231-.001-1.744-1.12l-1.464-3.192q-.512-1.118.152-2.153t1.893-1.035h-.712q-3.375 0-3.375-3.375v-.25q0-3.375 3.375-3.375m7.875 17H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 18.75");
}

</style>
