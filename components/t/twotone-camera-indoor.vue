<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0hzbaczh"/><path class="wdi2ektfo"/><path class="fhlpeqbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-camera-indoor" /></template>
<style>
.fhlpeqbhg {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm6 16H6v-9l6-4.5l6 4.5z");
}

.j0hzbaczh {
  fill: currentColor;
  d: path("M6 10v9h12v-9l-6-4.5zm8 2v1l2-1.06v4.12L14 15v1c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1h4c.55 0 1 .45 1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wdi2ektfo {
  fill: currentColor;
  d: path("M8 12v4c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-1l2 1.06v-4.12L14 13v-1c0-.55-.45-1-1-1H9c-.55 0-1 .45-1 1");
}

</style>
