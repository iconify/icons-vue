<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2ngtib3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-vpn-key-off" /></template>
<style>
.r2ngtib3u {
  fill: currentColor;
  d: path("M20.83 18H21v-4h2v-4H12.83zm-1.05 4.61l1.41-1.41L2.81 2.81L1.39 4.22l2.59 2.59A6.01 6.01 0 0 0 1 12c0 3.31 2.69 6 6 6c2.21 0 4.15-1.2 5.18-2.99zM8.99 11.82c.01.06.01.12.01.18c0 1.1-.9 2-2 2s-2-.9-2-2s.9-2 2-2c.06 0 .12 0 .18.01z");
}

</style>
