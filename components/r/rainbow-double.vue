<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocr3ajawv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rainbow-double" /></template>
<style>
.ocr3ajawv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 16.5q0-4.246 3.002-7.248T12 6.25t7.248 3.002T22.25 16.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m16.437-6.187Q15.624 7.75 12 7.75t-6.187 2.563q-2.294 2.293-2.535 5.437h2.261q.232-2.213 1.865-3.846Q9.308 10 12 10t4.596 1.904q1.633 1.633 1.865 3.846h2.261q-.241-3.144-2.535-5.437m-2.651 2.651Q14.071 11.5 12 11.5t-3.536 1.464q-1.191 1.192-1.413 2.786h9.898q-.222-1.594-1.413-2.786");
}

</style>
