<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgx6647tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-button-fill-sharp" /></template>
<style>
.rgx6647tg {
  fill: currentColor;
  d: path("M6 21V3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1m6.01-4H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
