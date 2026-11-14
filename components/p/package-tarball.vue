<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw1q4kndl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:package-tarball" /></template>
<style>
.tw1q4kndl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.75h14q1.346 0 2.298.952T22.25 6q0 2.208-1.5 2.916V18.5q0 2.75-2.75 2.75H6q-2.75 0-2.75-2.75V8.916Q1.75 8.208 1.75 6q0-1.346.952-2.298T5 2.75m-.25 6.495V18.5q0 1.25 1.25 1.25h12q1.25 0 1.25-1.25V9.245q-.122.005-.25.005H5q-.128 0-.25-.005m9.75 2.505h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
