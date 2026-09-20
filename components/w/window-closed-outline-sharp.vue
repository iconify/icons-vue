<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly--ymb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:window-closed-outline-sharp" /></template>
<style>
.ly--ymb3a {
  fill: currentColor;
  d: path("M5 20V4h14v16zm1-8.5h5.23v-.77h1.54v.77H18V5H6zM6 19h12v-6.5H6zm0 0h12z");
}

</style>
