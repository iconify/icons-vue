<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnwc5hvbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:media-bluetooth-on" /></template>
<style>
.dnwc5hvbs {
  fill: currentColor;
  d: path("M4.762 18.93q-.877-.876-.877-2.122q0-1.247.877-2.124q.877-.876 2.123-.876q.575 0 1.091.204q.516.205.909.615V4.192h4.884v2.539H9.885v10.077q0 1.246-.877 2.123t-2.123.877t-2.123-.877m11.815 1.877v-4.82l-2.943 2.943l-.58-.581l3.35-3.35l-3.4-3.35l.58-.58l2.943 2.942v-4.82h.33l3.259 3.258l-2.6 2.55l2.6 2.55l-3.208 3.258zm.765-1.647l1.612-1.611l-1.612-1.561zm0-5.15l1.612-1.561l-1.612-1.611z");
}

</style>
