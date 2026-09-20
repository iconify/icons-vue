<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea3ri1q9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:near-me-sharp" /></template>
<style>
.ea3ri1q9g {
  fill: currentColor;
  d: path("m12.9 21l-2.85-7.05L3 11.1V9.7L21 3l-6.7 18z");
}

</style>
