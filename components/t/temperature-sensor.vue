<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bezg5kbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:temperature-sensor" /></template>
<style>
.bezg5kbph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.384 8.616q0-.878-.438-1.574q.451-.605.955-1.588q1.01-1.971 2.246-2.219q.073-.014.141-.042t.129-.07t.114-.093q.052-.053.093-.114t.069-.13t.043-.14q.014-.073.014-.147t-.015-.146q-.014-.073-.042-.141t-.07-.129t-.093-.114q-.053-.052-.114-.093t-.13-.069t-.14-.043q-.073-.014-.147-.014t-.146.015q-1.947.389-3.287 3.005q-.388.756-.711 1.223q-.657-.377-1.471-.377q-1.243 0-2.121.879l-1.768 1.768q-.879.878-.879 2.121q0 .849.411 1.529L2.97 19.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l8.057-8.057q.68.411 1.529.411q1.243 0 2.121-.879l1.768-1.768q.879-.878.879-2.121");
}

</style>
