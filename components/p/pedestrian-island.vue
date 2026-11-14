<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcdwgx-ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pedestrian-island" /></template>
<style>
.tcdwgx-ms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3Q9.5 3 9.5 5.5T12 8q1.036 0 1.768-.732T14.5 5.5t-.732-1.768T12 3M8.75 14.75H6.5q-.75 0-.75.75v3.25h12.5V15.5q0-.75-.75-.75zm7.25-1.5h1.5q2.25 0 2.25 2.25v3.25h1.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75V15.5q0-2.25 2.25-2.25H8v-.5q0-3.5 4-3.5t4 3.5zm-6.5 0v-.5q0-2 2.5-2t2.5 2v.5z");
}

</style>
