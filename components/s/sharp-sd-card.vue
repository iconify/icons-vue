<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2qvs1byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sd-card" /></template>
<style>
.i2qvs1byi {
  fill: currentColor;
  d: path("M20 2H10L4 8v14h16zm-8 6h-2V4h2zm3 0h-2V4h2zm3 0h-2V4h2z");
}

</style>
