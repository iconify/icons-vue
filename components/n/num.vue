<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1mf8bbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:num" /></template>
<style>
.p1mf8bbau {
  fill: var(--svg-color--0000d8, #0000d8);
  d: path("M9 4.8v8.4l6 6v-8.4zm12 0h-6v6l4.2 4.182L15 19.2h6zm-12 0H3v14.4h6v-6L4.8 9z");
}

</style>
