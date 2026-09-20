<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1a9qksgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:on-hub-device" /></template>
<style>
.f1a9qksgq {
  fill: currentColor;
  d: path("M8 21v-2h8v2zm0-3L7 5.15q-.075-.875.525-1.513T9 3h6q.875 0 1.475.637T17 5.15L16 18z");
}

</style>
