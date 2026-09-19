<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xep23pbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-smartphone" /></template>
<style>
.xep23pbiq {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 18H7V5h10z");
}

</style>
