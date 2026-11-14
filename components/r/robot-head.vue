<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0q398pdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:robot-head" /></template>
<style>
.b0q398pdt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5q-2 0-2 2q0 1.581 1.25 1.912v.838H8.375q-2.123 0-3.624 1.501T3.25 11.375v5.25q0 2.123 1.501 3.624t3.624 1.501h7.25q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624T15.625 6.25H12.75v-.838Q14 5.081 14 3.5q0-2-2-2M8.75 9.75q2.5 0 2.5 2.5t-2.5 2.5t-2.5-2.5t2.5-2.5m9 2.5q0 2.5-2.5 2.5t-2.5-2.5t2.5-2.5t2.5 2.5m-2 5.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 16.75h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
