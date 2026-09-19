<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw7l5pbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-hotel-class" /></template>
<style>
.qw7l5pbdn {
  fill: currentColor;
  d: path("M8.58 10H1l6.17 4.41L4.83 22L11 17.31L17.18 22l-2.35-7.59L21 10h-7.58L11 2zm12.78 12l-1.86-6.01L23.68 13h-3.44l-3.08 2.2l1.46 4.72zM17 8l-1.82-6l-1.04 3.45l.77 2.55z");
}

</style>
