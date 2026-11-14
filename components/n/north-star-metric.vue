<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwjdorbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:north-star-metric" /></template>
<style>
.cwjdorbfp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.261 7.222l-.655-2.311h-.001Q13.261 3.698 12 3.698t-1.606 1.213l-.655 2.311q-.114.403-.517.517l-2.311.656Q5.698 8.739 5.698 10t1.213 1.606l2.311.655q.403.114.517.517l.656 2.311q.344 1.213 1.605 1.213t1.606-1.213l.655-2.311q.114-.403.517-.517l2.311-.656q1.213-.344 1.213-1.605t-1.213-1.606l-2.311-.655q-.403-.114-.517-.517M21.5 19.75h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
