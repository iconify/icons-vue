<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oww8-nbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:travel-adapter-plug" /></template>
<style>
.oww8-nbnb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3v5.25h4.5V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.25h.75q1.76 0 3.005 1.245T20.75 12.5V18q0 1.76-1.245 3.005T16.5 22.25h-9q-1.76 0-3.005-1.245T3.25 18v-5.5q0-1.76 1.245-3.005T7.5 8.25h.75V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q8.926 2.25 9 2.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T9.75 3m-1.5 12.25Q8.25 19 12 19t3.75-3.75T12 11.5t-3.75 3.75");
}

</style>
