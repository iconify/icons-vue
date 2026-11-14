<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdp6cujdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:roof-bolter" /></template>
<style>
.kdp6cujdj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.25h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T17 3.75h-4.25v9h4.75q1.968 0 3.359 1.391T22.25 17.5t-1.391 3.359T17.5 22.25h-11q-1.968 0-3.359-1.391T1.75 17.5t1.391-3.359T6.5 12.75h4.75v-9H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.25 7 2.25M6.5 15.5q-2 0-2 2t2 2q.828 0 1.414-.586T8.5 17.5t-.586-1.414T6.5 15.5m9 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
