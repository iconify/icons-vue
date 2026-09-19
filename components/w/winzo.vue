<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s36p55y6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:winzo" /></template>
<style>
.s36p55y6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.262 18.291L29 24.461l-7.941 4.467m21.235-4.93c-1.513 10.104-10.93 18.296-21.032 18.298h-.002c-10.103 0-17.066-8.19-15.552-18.294V24C7.221 13.896 16.638 5.705 26.741 5.705c10.103-.001 17.066 8.19 15.552 18.293z");
}

</style>
