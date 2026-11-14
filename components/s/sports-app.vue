<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsj7adc1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-app" /></template>
<style>
.wsj7adc1o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.875 1.75h4.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-4.25q-2.123 0-3.624-1.501T4.75 17.125V6.875q0-2.123 1.501-3.624T9.875 1.75m.875 2.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T10 5.25t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T14 5.25t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014zm4.432 5.318Q13.864 8.5 12.001 8.5h-.002q-1.863 0-3.181 1.318T7.5 13t1.318 3.182T12 17.5t3.182-1.318T16.5 13t-1.318-3.182");
}

</style>
