<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xijvqibal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-rows-sharp" /></template>
<style>
.xijvqibal {
  fill: currentColor;
  d: path("M21 21H3v-4.65h18zm0-6.65H3V9.625h18zm0-6.725H3V3h18z");
}

</style>
