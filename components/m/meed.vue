<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-oihkai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:meed" /></template>
<style>
.mn-oihkai {
  fill: var(--svg-color--e45c5c, #e45c5c);
  d: path("M8.182 16.636H4.909V3h3.818l3 8.727L15.273 3h3.818v18h-3.273V9l-3 7.636h-2.182L8.182 9z");
}

</style>
