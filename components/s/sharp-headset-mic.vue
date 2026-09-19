<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7lukhbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-headset-mic" /></template>
<style>
.f7lukhbsg {
  fill: currentColor;
  d: path("M11.4 1.02C6.62 1.33 3 5.51 3 10.31V20h6v-8H5v-1.71C5 6.45 7.96 3.11 11.79 3A7 7 0 0 1 19 10v2h-4v8h4v1h-7v2h9V10c0-5.17-4.36-9.32-9.6-8.98");
}

</style>
