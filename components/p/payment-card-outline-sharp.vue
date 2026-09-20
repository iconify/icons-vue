<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7v1fkb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:payment-card-outline-sharp" /></template>
<style>
.x7v1fkb2p {
  fill: currentColor;
  d: path("M3 19V4.98h18V19zm1-1h16V5.98H4zm1.77-1.73h8.403L9.827 7.711H5.769zm7.5-7.097h4.96V7.711h-4.96zM4 18V5.98z");
}

</style>
