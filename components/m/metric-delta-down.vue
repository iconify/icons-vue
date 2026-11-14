<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpo-oobmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:metric-delta-down" /></template>
<style>
.zpo-oobmg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.409 6.25H5.591q-1.457 0-2.175 1.268q-.719 1.268.031 2.518l2.909 4.849q.728 1.214 2.144 1.214t2.144-1.214l2.909-4.849q.75-1.25.031-2.518q-.718-1.268-2.175-1.268m10.091 5H17q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
