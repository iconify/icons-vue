<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlz_l_b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-nearby-error" /></template>
<style>
.zlz_l_b8p {
  fill: currentColor;
  d: path("m12 7.57l4.42 4.42L12 16.41l-4.42-4.42zm0 11.62l-7.2-7.2l7.2-7.2l6 6V7.16l-4.58-4.58c-.78-.78-2.05-.78-2.83 0l-8.01 8c-.78.78-.78 2.05 0 2.83l8.01 8c.78.78 2.05.78 2.83 0L18 16.82v-3.63zm8 .81h2v2h-2zm2-10h-2v8h2z");
}

</style>
