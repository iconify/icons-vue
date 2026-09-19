<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o37fdubgm"/><path class="lb84uxq5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-colorize" /></template>
<style>
.lb84uxq5v {
  fill: currentColor;
  d: path("m20.71 5.63l-2.34-2.34c-.2-.2-.45-.29-.71-.29s-.51.1-.7.29l-3.12 3.12l-1.93-1.91l-1.41 1.41l1.42 1.42L3 16.25V21h4.75l8.92-8.92l1.42 1.42l1.41-1.41l-1.92-1.92l3.12-3.12c.4-.4.4-1.03.01-1.42M6.92 19L5 17.08l8.06-8.06l1.92 1.92zm8.98-9.97l-.93-.93l2.69-2.69l.92.92z");
}

.o37fdubgm {
  fill: currentColor;
  d: path("m15.896 9.023l-.92-.92L17.67 5.41l.92.92z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
