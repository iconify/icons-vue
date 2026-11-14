<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im2grrb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:open-house" /></template>
<style>
.im2grrb5y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.535 9.637L18.75 8.149V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 2.75h-2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.315l-.59-.491q-2.16-1.799-4.32 0L3.465 9.637q-1.214 1.011-1.215 2.592v6.146q0 1.398.989 2.386q.988.989 2.386.989H10.5q-1.411 0-1.937-.884q-.849.475-1.812.135l-1.249-.441Q4.001 20.031 4 18.439V14.49q0-1.201.998-1.869q.998-.669 2.109-.211l1.249.514l.001.001q.541.222.872.586q.505-.261 1.271-.261H12q2.25 0 2.25 2.25v4q0 2.25-2.25 2.25h6.375q3.375 0 3.375-3.375v-6.146q-.001-1.581-1.215-2.592M17.25 6.899l-1-.833V4.25h1z");
}

</style>
