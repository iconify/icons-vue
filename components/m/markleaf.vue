<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ec_qi7bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:markleaf" /></template>
<style>
.ec_qi7bee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.023 3.5c.757-.003 10.125 4.519 12.982 15.182c1.963 7.33.39 15.64-.765 17.698s-5.06 8.12-12.216 8.12s-11.723-6.705-12.558-8.713s-2.549-10.48-.256-17.105C14.525 9.104 23.266 3.503 24.023 3.5m.001 8.644v25.129m-6.097-12.531h12.195m-12.164-6.06h12.13");
}

</style>
