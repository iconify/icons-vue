<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzjxcqbcm"/><circle class="soci7ctjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-attribution" /></template>
<style>
.soci7ctjl {
  cx: 12px;
  cy: 6.5px;
  r: 1.5px;
  fill: currentColor;
}

.yzjxcqbcm {
  fill: currentColor;
  d: path("M12 8.5c-.91 0-2.75.46-2.75 1.38v4.62h1.5V19h2.5v-4.5h1.5V9.88c0-.91-1.84-1.38-2.75-1.38M12 2C6.47 2 2 6.47 2 12s4.47 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8");
}

</style>
