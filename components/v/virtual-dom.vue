<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3ca0eflp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:virtual-dom" /></template>
<style>
.h3ca0eflp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.625 1.75h.75q3.375 0 3.375 3.375v.25q0 3.182-3 3.364V11H18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.074q.976.202 1.725.951Q21.5 16.8 21.5 18.25t-1.025 2.475T18 21.75q-3.5 0-3.5-3.5q0-3.102 2.75-3.455V12.5H6.75v2.295q2.75.353 2.75 3.455q0 3.5-3.5 3.5t-3.5-3.5q0-3.102 2.75-3.455V11.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 11h5.25V8.739q-3-.182-3-3.364v-.25q0-3.375 3.375-3.375");
}

</style>
