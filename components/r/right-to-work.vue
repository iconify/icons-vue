<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9cnbevgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:right-to-work" /></template>
<style>
.n9cnbevgc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.875 1.75h-9.75q-3.375 0-3.375 3.375v13.75q0 3.375 3.375 3.375h9.75q3.375 0 3.375-3.375V5.125q0-3.375-3.375-3.375M8 8.5q0-3.998 3.996-4H12q1.657 0 2.828 1.172Q16 6.843 16 8.5q0 4-4 4t-4-4m3 8.939l3.47-3.469q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-4 4q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 15.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
