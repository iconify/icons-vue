<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m613uvbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:obot" /></template>
<style>
.m613uvbqw {
  fill: var(--svg-color--fe0000, #fe0000);
  fill-rule: evenodd;
  d: path("M3 3h7.2v3h3.6V3H21v7.2h-3v3.6h3V21h-7.2v-3h-3.6v3H3v-7.2h3v-3.6H3zm4.2 7.2v3.6h3v3h3.6v-3h3v-3.6h-3v-3h-3.6v3zM4.8 4.8h3.6v3.6H4.8zm0 10.8h3.6v3.6H4.8zM19.2 4.8h-3.6v3.6h3.6zm-3.6 10.8h3.6v3.6h-3.6z");
}

</style>
