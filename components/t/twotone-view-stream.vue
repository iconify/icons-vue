<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf527bb2u"/><path class="z1vyudaod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-stream" /></template>
<style>
.hf527bb2u {
  fill: currentColor;
  d: path("M19 17H5v-4h14zM5 11V7h14v4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z1vyudaod {
  fill: currentColor;
  d: path("M3 7v10c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2m16 10H5v-4h14zM5 11V7h14v4z");
}

</style>
