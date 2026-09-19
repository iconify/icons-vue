<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtc0wbgux"/><path class="be625c6pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-screenshot" /></template>
<style>
.be625c6pp {
  fill: currentColor;
  d: path("M7 3h10v1H7zm0 17h10v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.gtc0wbgux {
  fill: currentColor;
  d: path("M17 1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 21H7v-1h10zm0-3H7V6h10zm0-14H7V3h10zM9.5 8.5H12V7H8v4h1.5zM12 17h4v-4h-1.5v2.5H12z");
}

</style>
