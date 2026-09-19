<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3i-_ibsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-contacts" /></template>
<style>
.y3i-_ibsb {
  fill: currentColor;
  d: path("M20 0H4v2h16zM4 24h16v-2H4zM22 4H2v16h20zM12 6.75c1.24 0 2.25 1.01 2.25 2.25s-1.01 2.25-2.25 2.25S9.75 10.24 9.75 9S10.76 6.75 12 6.75M17 17H7v-1.5c0-1.67 3.33-2.5 5-2.5s5 .83 5 2.5z");
}

</style>
