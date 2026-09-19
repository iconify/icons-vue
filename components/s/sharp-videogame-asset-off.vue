<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpzg27brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-videogame-asset-off" /></template>
<style>
.fpzg27brb {
  fill: currentColor;
  d: path("M20.83 18H22V6H8.83zM17.5 9c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m3.69 12.19L2.81 2.81L1.39 4.22L3.17 6H2v12h13.17l4.61 4.61zM9 13v2H7v-2H5v-2h2V9.83L10.17 13z");
}

</style>
