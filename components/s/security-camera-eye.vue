<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td-9mthls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:security-camera-eye" /></template>
<style>
.td-9mthls {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22.25 5.5v8q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.25h-3.14l.015.04q.602 1.654-.142 3.249t-2.399 2.198l-6.578 2.394q-1.654.602-3.249-.142T3.059 15.59l-.684-1.88q-.602-1.654.142-3.249t2.399-2.198l6.578-2.394q1.654-.602 3.249.142t2.198 2.399l.124.34h3.685V5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M9.5 9.5q-4.25 0-4.25 2.5t4.25 2.5t4.25-2.5T9.5 9.5");
}

</style>
