<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0n3o4b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-stable-sharp" /></template>
<style>
.y0n3o4b_x {
  fill: currentColor;
  d: path("M3 19V5h18v14zm13.975-1l2.3-8.689L7.075 6l-2.3 8.63z");
}

</style>
