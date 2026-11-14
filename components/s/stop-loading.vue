<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6zmzpb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stop-loading" /></template>
<style>
.o6zmzpb-n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.248 4.752Q16.246 1.75 12 1.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014q3.624 0 6.187 2.563T20.75 12t-2.563 6.187T12 20.75t-6.187-2.563T3.25 12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.149 0-.287.057t-.243.163t-.163.243q-.057.138-.057.287q0 4.246 3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248M8.5 11q0-2.5 2.5-2.5h2q2.5 0 2.5 2.5v2q0 2.5-2.5 2.5h-2q-2.5 0-2.5-2.5z");
}

</style>
