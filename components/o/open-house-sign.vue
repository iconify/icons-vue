<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i06fwybnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:open-house-sign" /></template>
<style>
.i06fwybnc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 21.25h17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.954L12.714 4.77q-.028-.085-.074-.161q-.047-.076-.11-.139t-.139-.11t-.161-.074q-.07-.022-.143-.031q-.074-.009-.147-.003q-.074.006-.145.027t-.137.053q-.066.034-.124.08t-.105.102t-.084.121t-.059.135L6.454 19.75H3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014m11.018-6l1.452 4.5H8.03l1.452-4.5zm-.483-1.5h-4.07L12 7.443z");
}

</style>
