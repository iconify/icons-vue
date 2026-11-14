<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cengdz08g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stethoscope" /></template>
<style>
.cengdz08g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.5V8q0 3.75 3.75 3.75T12.25 8V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V8q0 2.175-1.538 3.712q-1.265 1.266-2.962 1.49V15.5q0 4 4 4t4-4v-.31q-2-.345-2-2.69q0-2.75 2.75-2.75t2.75 2.75q0 2.345-2 2.69v.31q0 2.278-1.611 3.889T13.25 21t-3.889-1.611T7.75 15.5v-2.298q-1.697-.224-2.962-1.49Q3.25 10.175 3.25 8V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q3.926 2.75 4 2.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
