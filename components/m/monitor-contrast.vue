<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdyx-2b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:monitor-contrast" /></template>
<style>
.mdyx-2b9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h10.25q2.123 0 3.624 1.501t1.501 3.624v4.25q0 2.123-1.501 3.624t-3.624 1.501H12.75v2.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 19.75h3.25v-2.5H6.875q-2.123 0-3.624-1.501T1.75 12.125v-4.25q0-2.123 1.501-3.624T6.875 2.75m2.12 4.245Q7.75 8.24 7.75 10t1.245 3.005T12 14.25t3.005-1.245T16.25 10t-1.245-3.005T12 5.75h-.002q-1.759.001-3.003 1.245");
}

</style>
