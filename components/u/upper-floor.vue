<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjww8ybfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:upper-floor" /></template>
<style>
.qjww8ybfm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 17.25v3.5H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.75V8.5q0-.158-.063-.302q-.064-.144-.18-.251l-6-5.5q-.052-.047-.111-.084t-.124-.062t-.134-.038T12 2.25t-.138.013t-.134.038t-.124.062t-.111.084l-6 5.5q-.116.107-.18.251T5.25 8.5zm1.5.75v2.75h10.5V18zm10.5-1.5H6.75v-2.826q.337.076.75.076h9q.413 0 .75-.076zM12 4.017l4.072 3.733H7.928z");
}

</style>
