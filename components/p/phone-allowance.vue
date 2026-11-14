<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0vamvkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-allowance" /></template>
<style>
.aq0vamvkl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.125 1.75h-4.25q-2.123 0-3.624 1.501T4.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h4.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T14.125 1.75M7.75 11q0-1.76 1.245-3.005T12 6.75t3.005 1.245T16.25 11t-1.245 3.005T12 15.25t-3.005-1.245T7.75 11m5.75 6.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
