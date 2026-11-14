<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mopkrgbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pill-scored" /></template>
<style>
.mopkrgbow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 10.5q0-3.624 2.563-6.187T12 1.75t6.187 2.563T20.75 10.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 9.75H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146m0 0q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v3q0 3.624-2.563 6.187T12 22.25t-6.187-2.563T3.25 13.5zm1.908 5.465q.523 1.469 1.715 2.662Q8.997 20.75 12 20.75t5.127-2.123q1.192-1.193 1.715-2.662q-.303.371-.655.722Q15.624 19.25 12 19.25t-6.187-2.563q-.352-.351-.655-.722");
}

</style>
