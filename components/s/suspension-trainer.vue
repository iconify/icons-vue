<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhchrb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:suspension-trainer" /></template>
<style>
.oyhchrb8w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7.326V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4.826q-1.5.337-1.5 2.174q0 1.424.901 1.947L6.649 16.25H6.25q-2.5 0-2.5 2.5t2.5 2.5h1.5q2.5 0 2.5-2.5q0-2.068-1.711-2.425L12 12.172l3.461 4.153q-1.711.357-1.711 2.425q0 2.5 2.5 2.5h1.5q2.5 0 2.5-2.5t-2.5-2.5h-.399l-4.002-4.803q.901-.523.901-1.947q0-1.837-1.5-2.174");
}

</style>
