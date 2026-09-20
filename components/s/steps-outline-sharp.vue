<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8dxu5bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:steps-outline-sharp" /></template>
<style>
.w8dxu5bts {
  fill: currentColor;
  d: path("M17.67 20h1.92l.41-1.575l-4.875-4.875L13.35 8.2l-3.536.827L9 8.244V4.625l-.7-.35L4.035 10h3.173zm-4.295 0h2.837l-9.4-9h-3.3zm-.365 1L2.002 11.016l5.987-8.002L10 3.99v4.023l4.002-1.027l1.989 6.002L21 17.998L20.25 21z");
}

</style>
