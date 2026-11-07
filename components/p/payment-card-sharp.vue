<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0k-y6cir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:payment-card-sharp" /></template>
<style>
.s0k-y6cir {
  fill: currentColor;
  d: path("M3 19V4.98h18V19zm2.77-2.73h8.403L9.827 7.711H5.769zm7.5-7.097h4.96V7.711h-4.96z");
}

</style>
