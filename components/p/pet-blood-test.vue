<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljk4lms7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-blood-test" /></template>
<style>
.ljk4lms7k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.414 2.031q.052-.065.117-.117q.117-.093.26-.134t.292-.025q.148.016.279.088q.13.072.224.188Q14.75 4.737 14.75 6q0 2.75-2.75 2.75T9.25 6q0-1.263 2.164-3.969M6.75 10.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7.5 10h9q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.75v7q0 3.75-3.75 3.75T8.25 18.5v-7H7.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m7.5.75v3.25h-4.5V11.5zm0 7v-2.25h-4.5v2.25q0 2.25 2.25 2.25t2.25-2.25");
}

</style>
