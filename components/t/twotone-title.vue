<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7ual1e1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-title" /></template>
<style>
.t7ual1e1t {
  fill: currentColor;
  d: path("M5 7h5.5v12h3V7H19V4H5z");
}

</style>
