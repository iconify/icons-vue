<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bk8yfrh6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pha" /></template>
<style>
.bk8yfrh6e {
  fill: var(--svg-color--d1ff52, #d1ff52);
  fill-rule: evenodd;
  d: path("M3 3h14.143v3.857H21V12h-3.857V6.857H6.857V12H3zm3.857 12.857h10.286V12H6.857zm0 0V21H3v-5.143z");
}

</style>
