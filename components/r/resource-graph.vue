<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5q33y33w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:resource-graph" /></template>
<style>
.z5q33y33w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 5q0-3.25 3.25-3.25T15.25 5q0 2.85-2.5 3.201v4.549H18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.829q.874.196 1.549.872q.952.953.951 2.298q.001 1.347-.951 2.3T18 21.752t-2.299-.953t-.951-2.298v-.002q-.001-1.346.951-2.298q.675-.676 1.549-.872V14.25H6.75v1.049q2.5.351 2.5 3.201q0 3.25-3.25 3.25T2.75 18.5q0-2.85 2.5-3.201V13.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 12.75h5.25V8.201Q8.75 7.85 8.75 5");
}

</style>
