<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka0exbbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tifi" /></template>
<style>
.ka0exbbmx {
  fill: var(--svg-color--00a3ff, #00a3ff);
  d: path("M3 14.7v-.18l6.412-6.57h2.97l2.318 2.394l-1.525 1.598l-2.273-2.38l-4.95 5.138zm18-5.4v.18l-6.413 6.57h-2.97L9.3 13.656l1.525-1.597l2.273 2.38l4.95-5.139z");
}

</style>
