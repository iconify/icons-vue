<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhmycf-9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soccer-trophy" /></template>
<style>
.hhmycf-9b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.75h1.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.844-3.301 6.954q-.361.589-.883 1.112q-1.413 1.412-3.316 1.64v2.044h1.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 19.25t.732-1.768t1.768-.732h1.5v-2.044q-1.903-.228-3.316-1.64q-.522-.523-.883-1.112Q3.75 9.844 3.75 5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75m10.75 6.323q.845-1.343.976-3.323h-.976zM6.25 9V5.75h-.976q.131 1.98.976 3.323z");
}

</style>
