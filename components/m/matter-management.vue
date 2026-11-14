<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz11lsgro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:matter-management" /></template>
<style>
.cz11lsgro {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.75 11.5q0-2.487-2.25-2.725V5.25q0-.149-.057-.287t-.163-.243l-1.75-1.75q-.105-.106-.243-.163T17 2.75h-4.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T12 3.5v5.25h-.689L9.53 6.97q-.105-.106-.243-.163T9 6.75H5q-1.139 0-1.945.805q-.805.806-.805 1.945v9q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75zM18 8.75h-4.5v-4.5h3.189L18 5.561z");
}

</style>
