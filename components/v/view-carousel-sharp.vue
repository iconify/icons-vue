<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrx3upght"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-carousel-sharp" /></template>
<style>
.jrx3upght {
  fill: currentColor;
  d: path("M3 16V8h3.346v8zm4.73 2V6h8.54v12zm9.924-2V8H21v8z");
}

</style>
