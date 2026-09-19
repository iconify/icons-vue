<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6_z4ub8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-gavel" /></template>
<style>
.c6_z4ub8t {
  fill: currentColor;
  d: path("M2 21h10c.55 0 1 .45 1 1s-.45 1-1 1H2c-.55 0-1-.45-1-1s.45-1 1-1M5.24 8.07l2.83-2.83L20.8 17.97c.78.78.78 2.05 0 2.83s-2.05.78-2.83 0zm8.49-5.66l2.83 2.83c.78.78.78 2.05 0 2.83l-1.42 1.42l-5.65-5.66l1.41-1.41c.78-.79 2.05-.79 2.83-.01m-9.9 7.07l5.66 5.66l-1.41 1.41c-.78.78-2.05.78-2.83 0l-2.83-2.83c-.78-.78-.78-2.05 0-2.83z");
}

</style>
