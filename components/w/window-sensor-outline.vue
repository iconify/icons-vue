<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nupsax-vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:window-sensor-outline" /></template>
<style>
.nupsax-vx {
  fill: currentColor;
  d: path("M21.5 9q-.213 0-.357-.144T21 8.5v-4q0-.213.144-.356T21.501 4t.356.144T22 4.5v4q0 .213-.144.356T21.499 9M4 20V4h14v16zm1-8.5h5.23v-.77h1.54v.77H17V5H5zM5 19h12v-6.5H5zm0 0h12z");
}

</style>
