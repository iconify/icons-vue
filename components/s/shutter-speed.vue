<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjf-hxbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shutter-speed" /></template>
<style>
.bjf-hxbqt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043Q14.074 3.5 14 3.5h-1.25v1.78q2.937.24 5.084 2.386q2.416 2.417 2.416 5.834t-2.416 5.834T12 21.75t-5.834-2.416Q3.75 16.917 3.75 13.5t2.416-5.834Q8.313 5.52 11.25 5.28V3.5H10q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q9.926 2 10 2m2.001 7h-.002q-1.863 0-3.181 1.318T7.5 13.5t1.318 3.182T12 18t3.182-1.318t1.318-3.181v-.002q0-1.863-1.318-3.181T12.001 9");
}

</style>
