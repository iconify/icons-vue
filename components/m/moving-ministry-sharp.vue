<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4cztrbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moving-ministry-sharp" /></template>
<style>
.s4cztrbuo {
  fill: currentColor;
  d: path("M2 20V4h12.077v16H9.923v-4.154h-3.77V20zm3.385-7.308h1.461v-1.461H5.385zm0-3.846h1.461V7.384H5.385zm3.846 3.846h1.461v-1.461H9.231zm0-3.846h1.461V7.384H9.231zm10 5.943l-.708-.689l1.594-1.6h-3.886v-1h3.886l-1.594-1.6l.708-.688L22.019 12z");
}

</style>
