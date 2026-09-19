<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9a713beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-devices-fold" /></template>
<style>
.l9a713beh {
  fill: currentColor;
  d: path("M17 3V-.03l-7 3V21h12V3zm3 16h-5.33L17 18V5h3zM2 3h2v2H2zm0 16h2v2H2zm0-4h2v2H2zm0-4h2v2H2zm0-4h2v2H2zm4-4h2v2H6zm0 16h2v2H6z");
}

</style>
