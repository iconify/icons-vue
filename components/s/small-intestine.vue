<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxl2asbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:small-intestine" /></template>
<style>
.wxl2asbzw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 3.25h-13q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 3.926 2.75 4t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h13q2.063 0 2.063 1.75T16.5 8.25h-9q-3.187 0-3.187 3t3.187 3h10q1.688 0 1.688 1.75T17.5 17.75H6q-3.25 0-3.25 3.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.25 1.75-2.25h11.5q3.188 0 3.188-3.25T17.5 12.75h-10q-1.687 0-1.687-1.5T7.5 9.75h9q3.563 0 3.563-3.25T16.5 3.25");
}

</style>
