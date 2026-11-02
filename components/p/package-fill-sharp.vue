<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qym8drbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-fill-sharp" /></template>
<style>
.qym8drbcr {
  fill: currentColor;
  d: path("M5.106 3.553A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 3.999v.001c.07.139.106.292.106.447v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V8c0-.155.036-.308.106-.447ZM5 19h14V9H5Z");
}

</style>
