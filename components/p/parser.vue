<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5ict9btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parser" /></template>
<style>
.i5ict9btf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4.5q0-2.75 2.75-2.75t2.75 2.75q0 2.345-2 2.69v.31H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.06q2 .345 2 2.69t-2 2.69V15H19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.06q2 .345 2 2.69q0 2.75-2.75 2.75t-2.75-2.75q0-2.345 2-2.69v-.31h-6.5v.31q2 .345 2 2.69q0 2.75-2.75 2.75T8.25 19.5q0-2.345 2-2.69v-1.06q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T11 15h3.25v-.31q-2-.345-2-2.69t2-2.69V9h-8.5v.31q2 .345 2 2.69q0 2.75-2.75 2.75T2.25 12q0-2.345 2-2.69V8.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 7.5h4.25v-.31q-2-.345-2-2.69");
}

</style>
