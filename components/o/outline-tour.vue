<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rflb66byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-tour" /></template>
<style>
.rflb66byw {
  fill: currentColor;
  d: path("M21 4H7V2H5v20h2v-8h14l-2-5zm-3.86 5.74l.9 2.26H7V6h11.05l-.9 2.26l-.3.74zM14 9c0 1.1-.9 2-2 2s-2-.9-2-2s.9-2 2-2s2 .9 2 2");
}

</style>
