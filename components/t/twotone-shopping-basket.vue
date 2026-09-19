<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8_hww0r"/><path class="y242v6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-shopping-basket" /></template>
<style>
.kl8_hww0r {
  fill: currentColor;
  d: path("m3.31 11l2.2 8.01L18.5 19l2.2-8zM12 17c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y242v6bvn {
  fill: currentColor;
  d: path("M22 9h-4.79l-4.38-6.56c-.19-.28-.51-.42-.83-.42s-.64.14-.83.43L6.79 9H2c-.55 0-1 .45-1 1c0 .09.01.18.04.27l2.54 9.27c.23.84 1 1.46 1.92 1.46h13c.92 0 1.69-.62 1.93-1.46l2.54-9.27L23 10c0-.55-.45-1-1-1M12 4.8L14.8 9H9.2zM18.5 19l-12.99.01L3.31 11H20.7zM12 13c-1.1 0-2 .9-2 2s.9 2 2 2s2-.9 2-2s-.9-2-2-2");
}

</style>
