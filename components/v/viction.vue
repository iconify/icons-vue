<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wky0-1b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:viction" /></template>
<style>
.wky0-1b3a {
  fill: var(--svg-color--f8f6d7, #f8f6d7);
  d: path("M21 3v7.788a36.4 36.4 0 0 1-9 1.123c-3.108 0-6.124-.39-9-1.123V3a36.4 36.4 0 0 0 9 1.123c3.108 0 6.124-.39 9-1.123M3 21v-7.788a36.4 36.4 0 0 1 9-1.123c3.108 0 6.124.39 9 1.123V21a36.4 36.4 0 0 0-9-1.123c-3.108 0-6.124.39-9 1.123");
}

</style>
