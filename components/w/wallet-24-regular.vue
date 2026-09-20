<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbep71y3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wallet-24-regular" /></template>
<style>
.hbep71y3q {
  fill: currentColor;
  d: path("M15.5 13.75a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1-.75-.75M3 5h.014A2.25 2.25 0 0 1 5.25 3h11.5A2.25 2.25 0 0 1 19 5.25v.837a3.25 3.25 0 0 1 2.5 3.163v8.5A3.25 3.25 0 0 1 18.25 21h-12A3.25 3.25 0 0 1 3 17.75zm15.25 2.5H4.5v10.25c0 .966.784 1.75 1.75 1.75h12A1.75 1.75 0 0 0 20 17.75v-8.5a1.75 1.75 0 0 0-1.75-1.75M17.5 6v-.75a.75.75 0 0 0-.75-.75H5.25a.75.75 0 0 0 0 1.5z");
}

</style>
