<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckn2phb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parental-control" /></template>
<style>
.ckn2phb0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.25h10.25q2.123 0 3.624 1.501t1.501 3.624v5.75q0 1.532-.782 2.74Q21.167 13 18 13q-3.238 0-3.48 2.995q-1.177.672-1.443 2.255H11.75v1.5H13q0 .812.3 1.5H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 19.75h3.25v-1.5H6.875q-2.123 0-3.624-1.501T1.75 13.125v-5.75q0-2.123 1.501-3.624T6.875 2.25m14.143 15.232q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
