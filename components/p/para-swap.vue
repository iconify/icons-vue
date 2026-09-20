<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8bnycchj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:para-swap" /></template>
<style>
.b8bnycchj {
  fill: var(--svg-color--2669f5, #2669f5);
  d: path("M21 19.2L12.675 4.8L4.35 19.2zM6.825 11.55L10.65 4.8H3zM17.6 17.294H7.75l4.925-8.52z");
}

</style>
