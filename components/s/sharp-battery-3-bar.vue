<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny06pgnel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-3-bar" /></template>
<style>
.ny06pgnel {
  fill: currentColor;
  d: path("M17 4v18H7V4h3V2h4v2zm-2 2H9v8h6z");
}

</style>
