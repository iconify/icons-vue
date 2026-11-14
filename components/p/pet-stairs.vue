<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn2ky5zej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-stairs" /></template>
<style>
.vn2ky5zej {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.75 21V6q0-3-4-3q-3.481 0-3.933 2.273q-.06.015-.117.04t-.109.059t-.098.076t-.084.091t-.068.104t-.05.113t-.031.12q-.01.062-.01.124v4.25H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.75 11v4.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m-4-16.5q1.768 0 2.286.75h-4.572q.518-.75 2.286-.75");
}

</style>
