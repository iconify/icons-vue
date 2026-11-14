<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzlyonw_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ping-pong-paddles-crossed" /></template>
<style>
.fzlyonw_y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.141 5.141Q1.75 6.532 1.75 8.5t1.391 3.359T6.5 13.25q1.581 0 2.791-.899L10.939 14L5.97 18.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163L12 15.061l4.97 4.969q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113L13.061 14l1.648-1.649q1.21.899 2.791.899q1.968 0 3.359-1.391T22.25 8.5t-1.391-3.359T17.5 3.75t-3.359 1.391T12.75 8.5q0 1.581.899 2.791L12 12.939l-1.649-1.648q.899-1.21.899-2.791q0-1.968-1.391-3.359T6.5 3.75T3.141 5.141");
}

</style>
