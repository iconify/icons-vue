<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke2lhm46y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-commute" /></template>
<style>
.ke2lhm46y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22.25 7.625q0-2.905-2.5-3.309V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.25h-3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T14.75 3v1.316q-2.334.377-2.489 2.934H8.5q-2.75 0-2.75 2.75v1.873q-.448.179-.896.571l-2.25 1.968v.001q-.854.746-.854 1.881v2.956q0 1.036.732 1.768t1.768.732h4.5q1.036 0 1.768-.732t.732-1.768v-2.956q0-1.135-.854-1.881l-2.25-1.97q-.448-.391-.896-.57V10q0-1.25 1.25-1.25h3.75v.125q0 3.375 3.375 3.375h3.25q3.375 0 3.375-3.375zm-4-3.375h-2v-.5h2z");
}

</style>
