<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo6zno-pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nfc-off" /></template>
<style>
.qo6zno-pa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.9 3H13v6.1m0 7.8V21H3V6.9m3.5 10.6h3m5.975-7.975q.147.147.275.309q.128.163.236.34t.195.365q.086.188.15.386q.064.197.104.4t.055.41t.007.414q-.009.207-.042.411m1.907-5.06q.166.197.316.406q.151.209.286.429q.135.219.253.448t.22.466q.101.236.184.48q.084.244.149.493q.066.249.113.502q.047.254.075.51t.038.513q.009.258-.001.515t-.038.513t-.076.51q-.047.253-.113.502t-.149.492q-.084.244-.186.481q-.101.236-.22.465M3.5 3.5l17 17");
}

</style>
