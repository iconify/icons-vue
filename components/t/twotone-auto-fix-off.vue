<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imn3itbkh"/><path class="yg1kipy9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-auto-fix-off" /></template>
<style>
.imn3itbkh {
  fill: currentColor;
  d: path("m4.417 18.174l5.466-5.466l1.414 1.414l-5.466 5.466z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yg1kipy9t {
  fill: currentColor;
  d: path("m20 7l.94-2.06L23 4l-2.06-.94L20 1l-.94 2.06L17 4l2.06.94zm-5.83 1.42l1.41 1.41l-1.46 1.46l1.41 1.41l2.17-2.17a.996.996 0 0 0 0-1.41l-2.83-2.83a.98.98 0 0 0-.7-.29c-.26 0-.51.1-.71.29l-2.17 2.17l1.41 1.41zM2.81 2.81L1.39 4.22l7.07 7.07l-6.17 6.17a.996.996 0 0 0 0 1.41l2.83 2.83c.2.2.45.3.71.3s.51-.1.71-.29l6.17-6.17l7.07 7.07l1.41-1.41zm3.02 16.78l-1.41-1.41l5.46-5.46l1.41 1.41z");
}

</style>
