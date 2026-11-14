<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4-sc823l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:person-nonbinary" /></template>
<style>
.u4-sc823l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m11 9.054V13.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.554q2.25.348 2.25 2.946q0 3-3 3t-3-3q0-2.598 2.25-2.946M4 21.25h9.884q-.634-.994-.634-2.25q0-1.76 1.245-3.005q.466-.467 1.005-.758v-.813q-2.099-1.174-5-1.174q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75M16 19q0-1.5 1.5-1.5T19 19t-1.5 1.5T16 19m1.5-.25q-.25 0-.25.25t.25.25t.25-.25t-.25-.25");
}

</style>
