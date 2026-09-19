<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjz_w7bch"/><path class="sk8j2ybdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-stop" /></template>
<style>
.sk8j2ybdw {
  fill: currentColor;
  d: path("M6 18h12V6H6zM8 8h8v8H8z");
}

.wjz_w7bch {
  fill: currentColor;
  d: path("M8 8h8v8H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
