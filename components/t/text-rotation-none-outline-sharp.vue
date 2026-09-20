<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0e-jhs0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-rotation-none-outline-sharp" /></template>
<style>
.k0e-jhs0x {
  fill: currentColor;
  d: path("M4 19v-2h13.2l-1.05-1.05l1.4-1.4L21 18l-3.45 3.45l-1.4-1.4L17.2 19zm2.9-5L11 3h2l4.1 11h-1.9l-.95-2.8H9.8l-1 2.8zm3.45-4.4h3.3l-1.6-4.55h-.1z");
}

</style>
