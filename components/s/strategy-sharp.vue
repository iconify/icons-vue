<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkicrc9ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:strategy-sharp" /></template>
<style>
.bkicrc9ty {
  fill: currentColor;
  d: path("m14 22l-6-3.5v-7l3.5-2.05v6.05h5V9.45L20 11.5v7zM5.5 11L2 9V5l3.5-2L9 5v4zm7.5 3V2h9l-2 3l2 3h-7v6z");
}

</style>
