<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haemuwbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-text-fill" /></template>
<style>
.haemuwbkx {
  fill: currentColor;
  d: path("M5 6a3 3 0 1 1 6 0v6a3 3 0 1 1-6 0Zm16 0a1 1 0 0 1 0 2h-2v5a1 1 0 0 1-2 0V8h-2a1 1 0 0 1 0-2ZM2 10a1 1 0 0 1 2 0v2c0 1.737.831 3.152 2.499 3.745c.481.171.988.257 1.499.255h.004a4.4 4.4 0 0 0 1.499-.255C11.169 15.152 12 13.737 12 12v-2a1 1 0 0 1 2 0v2c0 .887-.157 1.774-.514 2.588c-.808 1.846-2.519 3.036-4.486 3.337V20h3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3v-2.075c-1.967-.301-3.678-1.491-4.486-3.337C2.157 13.774 2 12.887 2 12Z");
}

</style>
