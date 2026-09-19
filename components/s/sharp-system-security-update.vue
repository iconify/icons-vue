<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c50kwtbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-system-security-update" /></template>
<style>
.c50kwtbiw {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 17H7V6h10zm-1-6h-3V8h-2v4H8l4 4z");
}

</style>
