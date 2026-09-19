<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_mv1k_6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-text-rotation-angleup" /></template>
<style>
.g_mv1k_6s {
  fill: currentColor;
  d: path("m16.76 9l1.41 1.41l-9.19 9.19l1.41 1.41l9.19-9.19L21 13.24V9zm-8.28 3.75l3.54-3.54l2.19.92l1.48-1.48L4.56 4.23L3.5 5.29l4.42 11.14l1.48-1.48zm-.82-1.72L5.43 6.16l4.87 2.23z");
}

</style>
