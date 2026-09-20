<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa41frb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vite" /></template>
<style>
.xa41frb-w {
  fill: var(--svg-color--007aff, #007aff);
  d: path("m3 7.725l5.625-1.35l-.563 14.063zm6.75-1.524L21 3.563L8.231 20.274L9.75 6.206z");
}

</style>
