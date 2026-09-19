<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-w1ih29f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-no-drinks" /></template>
<style>
.o-w1ih29f {
  fill: currentColor;
  d: path("M21.19 21.19L2.81 2.81L1.39 4.22l8.23 8.23L11 14v5H6v2h12v-.17l1.78 1.78zM13 19v-3.17L16.17 19zM7.83 5l-2-2H21v2l-6.2 6.97l-1.42-1.42L14.77 9h-2.94l-2-2h6.74l1.78-2z");
}

</style>
