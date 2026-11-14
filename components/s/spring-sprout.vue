<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj8-bfbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spring-sprout" /></template>
<style>
.xj8-bfbwa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 16.759v-2.526q-7-.318-7-6.733q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 6.75q4.358 0 6.299 2.646Q11.865 3.25 19 3.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 6.89-7 7.232v5.527q6.713.172 7.952 3.478q.026.069.038.142t.01.146q-.003.074-.02.146t-.047.139q-.031.068-.074.128t-.097.11t-.117.089t-.132.065q-.127.048-.263.048H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.136.048-.263q1.239-3.306 7.952-3.478m6.97-11.985q-.378 4.631-5.44 4.952q.378-4.631 5.44-4.952M5.787 8.278q.409 4.112 5.319 4.443q-.915-4.115-5.319-4.443");
}

</style>
