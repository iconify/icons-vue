<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1asobji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-obelisk" /></template>
<style>
.ii1asobji {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.754 5.926v-.001q.02-.198.136-.361l2.5-3.5q.086-.121.213-.2t.274-.104q.147-.024.292.009q.146.034.267.121q.102.072.174.174l2.5 3.5q.116.163.136.361v.001l1.433 14.324H19.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.821zm1.425.824l-1.35 13.5h6.342l-1.35-13.5zm2.864-1.5L12 3.79l-1.043 1.46z");
}

</style>
