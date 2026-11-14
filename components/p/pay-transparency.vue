<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acbox5byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pay-transparency" /></template>
<style>
.acbox5byh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 3.688q-4.87 0-7.149 3.936q-.05.086-.075.181q-.026.096-.026.195t.026.195q.025.095.075.181Q3.63 12.313 8.5 12.313t7.149-3.937q.05-.086.075-.181q.026-.096.026-.195t-.026-.195q-.025-.095-.075-.181Q13.37 3.688 8.5 3.688m.01 3.562q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T9.26 8t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 8t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm4.954 5.964Q12 14.679 12 16.75t1.464 3.536Q14.929 21.75 17 21.75t3.536-1.464Q22 18.821 22 16.75t-1.464-3.536Q19.071 11.75 17 11.75t-3.536 1.464");
}

</style>
