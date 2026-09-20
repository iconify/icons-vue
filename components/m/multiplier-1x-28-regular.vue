<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="w2xnnndkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:multiplier-1x-28-regular" /></template>
<style>
.w2xnnndkh {
  fill: currentColor;
  d: path("M11.5 8.75a.75.75 0 0 0-1.369-.423l-.188.28c-.502.755-1.053 1.585-2.579 2.5a.75.75 0 1 0 .772 1.286c.818-.49 1.411-.976 1.864-1.434v8.291a.75.75 0 1 0 1.5 0zm3.78 5.47a.75.75 0 1 0-1.06 1.06L15.94 17l-1.72 1.72a.75.75 0 0 0 1.06 1.06L17 18.06l1.72 1.72a.75.75 0 1 0 1.06-1.06L18.06 17l1.72-1.72a.75.75 0 0 0-1.06-1.06L17 15.94z");
}

</style>
