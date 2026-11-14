<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blda9wb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-museum" /></template>
<style>
.blda9wb5k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25h11q2.25 0 2.25 2.25T17.5 6.75h-.75v10.5h.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732H6.75q-1.036 0-1.768-.732T4.25 19.75q0-2.5 2.5-2.5h.5V6.75H6.5q-2.25 0-2.25-2.25T6.5 2.25m8.75 4.5h-6.5v10.5h6.5zm-2.5 8.75v-7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 7.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v7q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
