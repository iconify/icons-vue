<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qib4jnbcj"/><path class="u-pddjbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-forest" /></template>
<style>
.qib4jnbcj {
  fill: currentColor;
  d: path("M16 12L9 2L2 12h1.86L0 18h7v4h4v-4h7l-3.86-6z");
}

.u-pddjbzr {
  fill: currentColor;
  d: path("M20.14 12H22L15 2l-2.39 3.41L17.92 13h-1.95l3.22 5H24zM13 19h4v3h-4z");
}

</style>
