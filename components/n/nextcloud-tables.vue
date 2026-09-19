<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c0x-3nbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextcloud-tables" /></template>
<style>
.c0x-3nbfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.308v29.383h37V9.308zm0 14.224h37m-37 7.58h37m-12.33-15.17v22.75m-12.34-22.75v22.75M5.5 15.942h37");
}

</style>
