<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m32kc2wdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooltip-bottom" /></template>
<style>
.m32kc2wdl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 2.75h-15q-1.139 0-1.945.805q-.805.806-.805 1.945v8q0 2.75 2.75 2.75h4.584l2.28 3.647q.092.147.239.239q.126.079.273.104t.293-.009t.266-.12q.122-.087.201-.214l2.28-3.647H19.5q2.75 0 2.75-2.75v-8q0-2.75-2.75-2.75m-4 6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 9.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
