<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbrlgqv_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-format-indent-decrease" /></template>
<style>
.cbrlgqv_i {
  fill: currentColor;
  d: path("M11 17h10v-2H11zm-8-5l4 4V8zm0 9h18v-2H3zM3 3v2h18V3zm8 6h10V7H11zm0 4h10v-2H11z");
}

</style>
