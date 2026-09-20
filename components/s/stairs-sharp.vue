<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg47xybxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stairs-sharp" /></template>
<style>
.kg47xybxc {
  fill: currentColor;
  d: path("M6 18h4.425v-3.325H13V11.35h2.575V8H18V6h-4.425v3.325H11v3.325H8.425V16H6zm-3 3V3h18v18z");
}

</style>
