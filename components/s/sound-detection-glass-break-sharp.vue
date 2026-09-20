<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs5k8_ggt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sound-detection-glass-break-sharp" /></template>
<style>
.hs5k8_ggt {
  fill: currentColor;
  d: path("M3 16V3h18v2.05l-7.5 8.425l-4-4zm0 5v-2l6.5-6.525l4 4L21 8.05V21z");
}

</style>
