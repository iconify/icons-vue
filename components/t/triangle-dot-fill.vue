<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztxrzdbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-dot-fill" /></template>
<style>
.ztxrzdbht {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.7328 3.8869C10.2061 1.3716 13.7947 1.3715 15.268 3.8869L22.4623 16.172C23.9502 18.7134 22.1759 21.9998 19.1947 22.0002L4.8061 22.0002C1.8245 22.0001 0.0502 18.7136 1.5385 16.172L8.7328 3.8869ZM14 14C14 12.8954 13.1046 12 12 12C10.8954 12 10 12.8954 10 14C10 15.1046 10.8954 16 12 16C13.1046 16 14 15.1046 14 14Z");
}

</style>
