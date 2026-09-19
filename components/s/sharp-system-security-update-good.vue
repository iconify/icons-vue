<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k25incbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-system-security-update-good" /></template>
<style>
.k25incbyk {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 17H7V6h10zm-1-7.95l-1.41-1.41l-3.54 3.54l-1.41-1.41l-1.41 1.41L11.05 15z");
}

</style>
