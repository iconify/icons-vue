<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7nh1e2eq"/><path class="xazqpn84p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-computer" /></template>
<style>
.a7nh1e2eq {
  fill: currentColor;
  d: path("M4 6h16v10H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xazqpn84p {
  fill: currentColor;
  d: path("M20 18c1.1 0 1.99-.9 1.99-2L22 6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2H0v2h24v-2zM4 6h16v10H4z");
}

</style>
