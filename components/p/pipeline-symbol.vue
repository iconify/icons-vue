<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkaxftbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pipeline-symbol" /></template>
<style>
.xkaxftbxp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 8q0-2.25-2.25-2.25T6.25 8v.25H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 8.926 1.75 9v6q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.75V16q0 2.25 2.25 2.25T10.75 16v-.25h2.5V16q0 2.25 2.25 2.25T17.75 16v-.25h3.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.75V8q0-2.25-2.25-2.25T13.25 8v.25h-2.5zm-4.5 6.25h-3v-4.5h3zm7 0h-2.5v-4.5h2.5zm4.5 0v-4.5h3v4.5z");
}

</style>
