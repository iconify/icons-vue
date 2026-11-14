<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2ghzz-1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:static-site" /></template>
<style>
.g2ghzz-1j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 2.75 2.75 2.75h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0 1.346-.952 2.298T17 22.25H7q-1.346 0-2.298-.952T3.75 19V5q0-1.346.952-2.298T7 1.75m7.25.75q0-.149-.057-.287t-.162-.243l5.999 6q-.105-.106-.243-.163T19.5 7.75h-4q-1.25 0-1.25-1.25zM7 14.5q0 2.071 1.464 3.536Q9.929 19.5 12 19.5t3.536-1.464Q17 16.571 17 14.5t-1.464-3.536T12 9.5t-3.536 1.464Q7 12.429 7 14.5");
}

</style>
