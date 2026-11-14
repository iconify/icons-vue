<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmtm6jb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:zero-energy" /></template>
<style>
.cmtm6jb9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.426 4.692q-1.116-.548-1.873.438l-.002.003l-3.981 5.226q-.793 1.042-.212 2.216T7.25 13.75h.943q.352 0 .577.271t.16.617l-.417 2.224q-.238 1.279.964 1.776q1.202.496 1.935-.578l3.659-5.365q.748-1.097.127-2.272q-.62-1.174-1.948-1.173h-.798q-.369 0-.594-.293t-.13-.65l.497-1.864q.317-1.204-.799-1.751m5.324 14.247l-1.47-1.469q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T14 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2 2q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4.25-4.25q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
