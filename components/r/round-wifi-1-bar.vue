<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="l97nb-quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-wifi-1-bar" /></template>
<style>
.l97nb-quh {
  cx: 12px;
  cy: 18px;
  r: 2px;
  fill: currentColor;
}

</style>
