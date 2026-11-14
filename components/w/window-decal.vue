<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt1o4l4gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:window-decal" /></template>
<style>
.pt1o4l4gz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.875 1.75H5.125q-3.375 0-3.375 3.375v13.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375V5.125q0-3.375-3.375-3.375M7 6.25h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6.5q0 .149-.057.287t-.163.243l-3.5 3.5q-.105.106-.243.163t-.287.057H7q0 .149-.057.287t-.163.243l-1.5 1.5q-.105.106-.243.163T4.75 20t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T4 19.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l1.5-1.5q.105-.106.243-.163T6.25 17V7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 6.25");
}

</style>
