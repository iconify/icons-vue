<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smgkwab3e"/><path class="milyehbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-military-tech" /></template>
<style>
.milyehbul {
  fill: currentColor;
  d: path("M17 10.43V2H7v8.43c0 .35.18.68.49.86l4.18 2.51l-.99 2.34l-3.41.29l2.59 2.24L9.07 22L12 20.23L14.93 22l-.78-3.33l2.59-2.24l-3.41-.29l-.99-2.34l4.18-2.51c.3-.18.48-.5.48-.86m-6 .64l-2-1.2V4h2zm4-1.2l-2 1.2V4h2z");
}

.smgkwab3e {
  fill: currentColor;
  d: path("m13 11.07l2-1.2V4h-2zM9 4v5.87l2 1.2V4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
