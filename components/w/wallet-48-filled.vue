<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ux_e2wbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wallet-48-filled" /></template>
<style>
.ux_e2wbqh {
  fill: currentColor;
  d: path("M6 10v25.75A6.25 6.25 0 0 0 12.25 42h24.5A6.25 6.25 0 0 0 43 35.75v-17.5a6.25 6.25 0 0 0-5-6.125V10.25A4.25 4.25 0 0 0 33.75 6h-23.5a4.25 4.25 0 0 0-4.243 4zm29.5.25V12H10.25a1.75 1.75 0 1 1 0-3.5h23.5c.967 0 1.75.784 1.75 1.75M32.25 26h4.5a1.25 1.25 0 1 1 0 2.5h-4.5a1.25 1.25 0 1 1 0-2.5");
}

</style>
