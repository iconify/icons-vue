<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6zyg8bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smart-display" /></template>
<style>
.n6zyg8bov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 1.75h8.25q2.123 0 3.624 1.501t1.501 3.624v6.75q0 2.123-1.501 3.624t-3.624 1.501H12.75v2h2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.75v-2H7.875q-2.123 0-3.624-1.501T2.75 13.625v-6.75q0-2.123 1.501-3.624T7.875 1.75M8 4.5Q5.5 4.5 5.5 7v6.5Q5.5 16 8 16h8q2.5 0 2.5-2.5V7q0-2.5-2.5-2.5z");
}

</style>
