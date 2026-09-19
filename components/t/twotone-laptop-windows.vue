<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huhq7rrms"/><path class="xckz84bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-laptop-windows" /></template>
<style>
.huhq7rrms {
  fill: currentColor;
  d: path("M4 5h16v10H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xckz84bdu {
  fill: currentColor;
  d: path("M20 18v-1c1.1 0 1.99-.9 1.99-2L22 5c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2v1H0v2h24v-2zM4 5h16v10H4z");
}

</style>
