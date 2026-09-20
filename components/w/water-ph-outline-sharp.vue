<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxo-3gb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-ph-outline-sharp" /></template>
<style>
.yxo-3gb2a {
  fill: currentColor;
  d: path("M9 21.95q-3.05-.35-5.025-2.625T2 13.8q0-2.5 1.988-5.437T10 2q4.025 3.425 6.013 6.363T18 13.8v.2h-2v-.2q0-1.825-1.513-4.125T10 4.65Q7.025 7.375 5.513 9.675T4 13.8q0 2.425 1.4 4.1T9 19.925zm2 .05v-6h5v4h-3.5v2zm6 0v-6h1.5v2h2v-2H22v6h-1.5v-2.5h-2V22zm-4.5-3.5h2v-1h-2z");
}

</style>
