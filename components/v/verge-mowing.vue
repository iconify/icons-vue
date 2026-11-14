<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykd-w5y0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:verge-mowing" /></template>
<style>
.ykd-w5y0h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 14q0-2.238-1.541-2.935l4.686-6.815H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3q-.091 0-.18.022q-.088.022-.169.064t-.149.103t-.12.136l-5.277 7.676l-.105-.001H5q-1.346 0-2.298.952T1.75 14q0 2.404 1.778 3.03q-.278.596-.278 1.47q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h1.376q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-1.2-.523-1.876q1.023-.8 1.023-2.624");
}

</style>
