<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1hy-ls9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rolling-pin" /></template>
<style>
.y1hy-ls9h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 7.25h4q1.968 0 3.359 1.391q1.118 1.118 1.337 2.609H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.804q-.219 1.491-1.337 2.609Q15.968 16.75 14 16.75h-4q-1.968 0-3.359-1.391q-1.118-1.118-1.337-2.609H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.804q.219-1.491 1.337-2.609Q8.032 7.25 10 7.25");
}

</style>
