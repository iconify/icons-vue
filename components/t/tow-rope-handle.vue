<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye4wnfb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tow-rope-handle" /></template>
<style>
.ye4wnfb8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 3q0 13.75 9.25 13.75h3.25V15q0-2.25 2.25-2.25T21.25 15v5q0 2.25-2.25 2.25T16.75 20v-1.75H13.5Q2.75 18.25 2.75 3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T4.25 3");
}

</style>
