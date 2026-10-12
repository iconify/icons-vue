<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggdulzbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-tube-rack-sharp" /></template>
<style>
.ggdulzbvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18h18M4.5 18v3m15-3v3M6.25 3h3.5v12h-3.5v-1.75Zm8 0h3.5v12h-3.5v-1.75Zm-8 7.5h3.5m4.5-2h3.5");
}

</style>
