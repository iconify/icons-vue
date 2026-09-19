<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_1v8k5qn"/><path class="s3lw41b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-near-me" /></template>
<style>
.s3lw41b7q {
  fill: currentColor;
  d: path("m3 11.51l6.84 2.65L12.48 21h.98L21 3L3 10.53zm14.27-4.78l-4.24 10.13l-1.32-3.42l-.32-.83l-.82-.32l-3.43-1.33z");
}

.u_1v8k5qn {
  fill: currentColor;
  d: path("m11.39 12.61l.32.83l1.32 3.42l4.24-10.13l-10.13 4.24l3.42 1.33z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
