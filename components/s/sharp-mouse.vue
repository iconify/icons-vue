<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxgivab4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mouse" /></template>
<style>
.dxgivab4d {
  fill: currentColor;
  d: path("M13 1.07V9h7c0-4.08-3.05-7.44-7-7.93M4 15c0 4.42 3.58 8 8 8s8-3.58 8-8v-4H4zm7-13.93C7.05 1.56 4 4.92 4 9h7z");
}

</style>
