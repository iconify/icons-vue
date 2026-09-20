<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i087x5x5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-plug-sharp" /></template>
<style>
.i087x5x5v {
  fill: currentColor;
  d: path("M10.27 20v-2.654L7 14.077V8h2.346V4h1v4h3.308V4h1v4H17v6.077l-3.27 3.27V20z");
}

</style>
