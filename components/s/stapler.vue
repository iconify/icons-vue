<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gomdcvb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stapler" /></template>
<style>
.gomdcvb6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 15q0-4.625 3.503-7.112Q8.767 5.75 13.5 5.75H18q3.75 0 3.75 2.75V18q0 2.25-2.25 2.25h-15q-2.25 0-2.25-2.25zm18-6.5q0-1.25-2.25-1.25h-4.5q-9.266 0-9.726 7H20.25zM17 10.25h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 10.25");
}

</style>
