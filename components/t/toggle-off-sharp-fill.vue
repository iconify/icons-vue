<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xffydddrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-off-sharp-fill" /></template>
<style>
.xffydddrz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 5L21.5 5C22.3284 5 23 5.6716 23 6.5L23 17.5C23 18.3284 22.3284 19 21.5 19L2.5 19C1.6716 19 1 18.3284 1 17.5L1 6.5C1 5.6716 1.6716 5 2.5 5ZM6.5 9L9.5 9C10.3284 9 11 9.6716 11 10.5L11 13.5C11 14.3284 10.3284 15 9.5 15L6.5 15C5.6716 15 5 14.3284 5 13.5L5 10.5C5 9.6716 5.6716 9 6.5 9Z");
}

</style>
