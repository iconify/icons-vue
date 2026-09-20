<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpokk8bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-sensor-outline" /></template>
<style>
.cpokk8bda {
  fill: currentColor;
  d: path("M22 9q-.425 0-.712-.288T21 8V4q0-.425.288-.712T22 3t.713.288T23 4v4q0 .425-.288.713T22 9M3 21V3h16v18zm2-10h5v-1h2v1h5V5H5zm0 8h12v-6H5zm0 0h12z");
}

</style>
