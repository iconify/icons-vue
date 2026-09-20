<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb_8hwboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-image-24-filled" /></template>
<style>
.hb_8hwboz {
  fill: currentColor;
  d: path("M11 3H6a3 3 0 0 0-3 3v4.535A4 4 0 0 1 5 10h5a4 4 0 0 1 4 4v5c0 .729-.195 1.412-.535 2H18a3 3 0 0 0 3-3V8h-7.75A2.25 2.25 0 0 1 11 5.75zm10 3.5V6a3 3 0 0 0-3-3h-5.5v2.75c0 .414.336.75.75.75zM5 11a3 3 0 0 0-3 3v5c0 .556.151 1.077.415 1.524L5.91 17.03a2.25 2.25 0 0 1 3.182 0l3.494 3.494c.264-.447.415-.968.415-1.524v-5a3 3 0 0 0-3-3zm0 11a3 3 0 0 1-1.524-.415L6.97 18.09a.75.75 0 0 1 1.06 0l3.494 3.494A3 3 0 0 1 10 22zm5-7a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
