<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3td_g_af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-code-fill-sharp" /></template>
<style>
.q3td_g_af {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-1h16V9H4Zm6.707-6.293L9.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414l-2-2a.997.997 0 0 1 0-1.414l2-2a.999.999 0 1 1 1.414 1.414m4-1.414l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L14.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
