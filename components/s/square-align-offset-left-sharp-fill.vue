<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6l_u-bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-left-sharp-fill" /></template>
<style>
.j6l_u-bsb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2L21 2C21.5523 2 22 2.4477 22 3ZM15 10L15 17L17 17L17 10L15 10ZM11 7L11 16L13 16L13 7L11 7ZM7 7L7 11L9 11L9 7L7 7Z");
}

</style>
