<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esu5_7agu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-time-slider" /></template>
<style>
.esu5_7agu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.789 4.859l4.25-1.771q.961-.401 1.922 0l4.655 1.94q.384.16.769 0l2.904-1.21q1.234-.515 2.348.227t1.113 2.08v10.708q.001 1.667-1.539 2.308l-4.25 1.771q-.961.401-1.922 0l-4.655-1.94q-.384-.16-.769 0l-2.904 1.21q-1.234.515-2.348-.227t-1.113-2.08V7.167Q2.249 5.5 3.789 4.859M8.31 11.75H6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.81q.345 2 2.69 2t2.69-2h3.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.81q-.345-2-2.69-2t-2.69 2");
}

</style>
