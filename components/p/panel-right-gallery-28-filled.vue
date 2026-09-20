<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="y0c0kcc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-gallery-28-filled" /></template>
<style>
.y0c0kcc1p {
  fill: currentColor;
  d: path("M25.997 7.75A3.75 3.75 0 0 0 22.247 4H5.75A3.75 3.75 0 0 0 2 7.75v11.5A3.75 3.75 0 0 0 5.75 23h16.497a3.75 3.75 0 0 0 3.75-3.75V17.5H18v4H5.75a2.25 2.25 0 0 1-2.25-2.25V7.75A2.25 2.25 0 0 1 5.75 5.5H18v4h7.997zM18 16h7.997v-5H18z");
}

</style>
