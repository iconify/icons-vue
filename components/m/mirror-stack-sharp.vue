<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhlfhibbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mirror-stack-sharp" /></template>
<style>
.vhlfhibbg {
  fill: currentColor;
  d: path("M4 22V6h10v16zm12-4V4h-6V2h10v16z");
}

</style>
