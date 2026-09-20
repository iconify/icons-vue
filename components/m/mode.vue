<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njm0qxbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mode" /></template>
<style>
.njm0qxbux {
  fill: var(--svg-color--dffe00, #dffe00);
  d: path("M20.984 19.963h-3.511v-7.938l1.406-4.527l-.998-.355l-4.553 12.82h-2.672L6.1 7.143l-.994.355l1.405 4.527v7.941H3V4.034h5.227l3.243 9.118v2.68h1.06v-2.68l3.243-9.118H21v15.93z");
}

</style>
