<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt44v8b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scale-digital-counter" /></template>
<style>
.lt44v8b2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 2.25h-6.5q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h2.5v2.5H4.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-6.75v-2.5h2.5q2.5 0 2.5-2.5v-2q0-2.5-2.5-2.5M2.879 18.093l.545-2q.503-1.844 2.413-1.843h12.326q1.91-.001 2.413 1.843l.545 2q.324 1.192-.426 2.174q-.75.983-1.986.983H5.291q-1.236 0-1.986-.983q-.75-.982-.426-2.174");
}

</style>
