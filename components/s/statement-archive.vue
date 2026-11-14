<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxsgi8sgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:statement-archive" /></template>
<style>
.pxsgi8sgl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 7.25h-1.5V3.5q0-1.75-1.75-1.75H8q-1.75 0-1.75 1.75v3.75h-1.5q-3 0-3 3q0 1.243.879 2.121q.29.291.621.486V19.5q0 2.75 2.75 2.75h12q2.75 0 2.75-2.75v-6.643q.331-.195.621-.486q.879-.878.879-2.121q0-3-3-3M7.75 3.5q0-.25.25-.25h8q.25 0 .25.25v3.75h-8.5zm6.75 1h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T9.5 6h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14.5 4.5m-9.75 8.75h14.5v6.25q0 1.25-1.25 1.25H6q-1.25 0-1.25-1.25zm8.5 1h-2.5q-2 0-2 2t2 2h2.5q2 0 2-2t-2-2");
}

</style>
