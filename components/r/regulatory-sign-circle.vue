<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1vf07qtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:regulatory-sign-circle" /></template>
<style>
.d1vf07qtp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.51 4.129Q3.25 6.597 3.25 10q0 3.624 2.563 6.187q2.293 2.294 5.437 2.535V22q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.278q2.929-.225 5.121-2.232q-.088.015-.177.008t-.174-.034t-.161-.074t-.139-.11L5.72 4.78q-.063-.063-.11-.139q-.046-.076-.074-.161t-.034-.174t.008-.177m12.98 11.742q2.26-2.468 2.26-5.871q0-3.624-2.563-6.187T12 1.25q-3.403 0-5.871 2.26q.088-.015.177-.008t.174.034t.161.074t.139.11l11.5 11.5q.106.105.163.243t.057.287q0 .061-.01.121");
}

</style>
