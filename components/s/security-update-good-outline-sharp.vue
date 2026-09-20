<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bijnllbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:security-update-good-outline-sharp" /></template>
<style>
.bijnllbyc {
  fill: currentColor;
  d: path("M11.05 14.308L8.942 12.2l.708-.708l1.4 1.4l3.55-3.55l.708.708zM6 22V2h12v20zm1-2.5V21h10v-1.5zm0-1h10v-13H7zm0-14h10V3H7zm0 0V3zm0 15V21z");
}

</style>
