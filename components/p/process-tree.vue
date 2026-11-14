<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykgfhjadv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:process-tree" /></template>
<style>
.ykgfhjadv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.375 1.75h-.75q-3.375 0-3.375 3.375v.75q0 3.182 3 3.364v2.011H5.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.75 12v2.761q-3 .182-3 3.364v.75q0 3.375 3.375 3.375h.75q3.375 0 3.375-3.375v-.75q0-3.182-3-3.364V12.75h11.5v2.011q-3 .182-3 3.364v.75q0 3.375 3.375 3.375h.75q3.375 0 3.375-3.375v-.75q0-3.182-3-3.364V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-5.75V9.239q3-.182 3-3.364v-.75q0-3.375-3.375-3.375");
}

</style>
