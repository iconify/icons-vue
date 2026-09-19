<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw4hhxbzz"/><path class="td2kkx1ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-switch-left" /></template>
<style>
.sw4hhxbzz {
  fill: currentColor;
  d: path("M8.5 8.62v6.76L5.12 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.td2kkx1ph {
  fill: currentColor;
  d: path("M8.5 8.62v6.76L5.12 12zM10 5l-7 7l7 7zm4 0v14l7-7z");
}

</style>
