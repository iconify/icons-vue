<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxe57zbbc"/><path class="iz5m563rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-comment" /></template>
<style>
.cxe57zbbc {
  fill: currentColor;
  d: path("M20 17.17V4H4v12h14.83zM18 14H6v-2h12zm0-3H6V9h12zm0-3H6V6h12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.iz5m563rp {
  fill: currentColor;
  d: path("M4 18h14l4 4l-.01-18c0-1.1-.89-2-1.99-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2M4 4h16v13.17L18.83 16H4zm2 8h12v2H6zm0-3h12v2H6zm0-3h12v2H6z");
}

</style>
