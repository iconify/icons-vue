<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9z2avp9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smart-glasses-camera" /></template>
<style>
.i9z2avp9j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.01 5.25H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 6t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T12.76 6t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M7 8.25H6q-1.76 0-3.005 1.245T1.75 12.5t1.245 3.005T6 16.75h1q1.76 0 3.005-1.245T11.25 12.5q0-.126-.006-.25h1.512q-.006.124-.006.25q0 1.76 1.245 3.005T17 16.75h1q1.76 0 3.005-1.245T22.25 12.5t-1.245-3.005T18 8.25h-1q-1.76 0-3.005 1.245q-.573.573-.882 1.255h-2.226q-.309-.682-.882-1.255Q8.76 8.25 7 8.25");
}

</style>
