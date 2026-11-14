<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4vzr75fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:speed-limit-70" /></template>
<style>
.q4vzr75fq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M6 7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T6 8.5h3.69L7.043 16q-.05.141-.042.29t.072.284q.065.134.176.234t.251.149q.07.025.143.035t.147.007t.145-.022t.139-.05q.066-.032.125-.077q.06-.044.109-.099t.087-.118t.062-.133l3-8.5q.043-.122.043-.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T10.75 7zm9.5 0q-3.25 0-3.25 3.25v3.5q0 3.25 3.25 3.25t3.25-3.25v-3.5Q18.75 7 15.5 7");
}

</style>
