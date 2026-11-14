<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8jx01bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-pet-shop" /></template>
<style>
.z8jx01bqk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.558 3.212l-1.25 3q-.058.138-.058.288q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 7.25h.75V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7.25H21q.15 0 .288-.058q.138-.057.243-.163q.106-.105.163-.243q.056-.138.056-.288t-.058-.286l-1.25-3q-.042-.103-.113-.189q-.071-.085-.163-.147t-.199-.094q-.106-.032-.217-.032H4.25q-.111 0-.217.032q-.107.032-.199.094t-.163.147t-.113.189M5.25 19.75V7.25h13.5v12.5zm6.75-11q-2 0-2 2t2 2t2-2t-2-2M6 12.5q0-2 2-2t2 2t-2 2t-2-2m8 0q0-2 2-2t2 2t-2 2t-2-2m-2 1q-3.5 0-3.5 2.75T12 19t3.5-2.75T12 13.5");
}

</style>
