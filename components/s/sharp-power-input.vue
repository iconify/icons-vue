<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5uduuxtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-power-input" /></template>
<style>
.q5uduuxtq {
  fill: currentColor;
  d: path("M2 9v2h19V9zm0 6h5v-2H2zm7 0h5v-2H9zm7 0h5v-2h-5z");
}

</style>
