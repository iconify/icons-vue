<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk2-7obql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skip-back" /></template>
<style>
.pk2-7obql {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 19V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T5 4.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.25 5v14q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.75 19M15.816 6.313l-5.198 3.639Q9.551 10.698 9.551 12t1.067 2.049l5.198 3.638q1.243.871 2.589.17t1.345-2.218V8.361q.001-1.517-1.345-2.218t-2.589.17");
}

</style>
