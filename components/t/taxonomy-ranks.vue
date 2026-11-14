<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8__ab_og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:taxonomy-ranks" /></template>
<style>
.s8__ab_og {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-3.75 0-3.75 3.75q0 3.354 3 3.708v2.542H5.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.792q-3 .354-3 3.708q0 3.75 3.75 3.75T9.25 18q0-3.354-3-3.708V13.25h11.5v1.042q-3 .354-3 3.708q0 3.75 3.75 3.75T22.25 18q0-3.354-3-3.708V12.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-5.75V9.208q3-.354 3-3.708q0-3.75-3.75-3.75");
}

</style>
