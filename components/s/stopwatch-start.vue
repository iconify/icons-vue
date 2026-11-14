<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmbk1qbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stopwatch-start" /></template>
<style>
.pmbk1qbaa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.25v1.278q3.144.241 5.437 2.535q2.563 2.563 2.563 6.187t-2.563 6.187T12 22t-6.187-2.563T3.25 13.25t2.563-6.187q2.293-2.294 5.437-2.535V3.25H10q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.25 2.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014zm.024 6.921q-1.249-.741-2.511-.022T9 12.321v1.858q.001 1.453 1.263 2.172t2.511-.022l1.567-.928q1.227-.726 1.227-2.151t-1.227-2.151z");
}

</style>
