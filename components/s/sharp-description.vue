<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cziy3p7lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-description" /></template>
<style>
.cziy3p7lq {
  fill: currentColor;
  d: path("M14 2H4v20h16V8zm2 16H8v-2h8zm0-4H8v-2h8zm-3-5V3.5L18.5 9z");
}

</style>
