<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk06ssbdv"/><path class="wjbte45me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toggle-left-bold-duotone" /></template>
<style>
.pk06ssbdv {
  fill: currentColor;
  d: path("M8 6H16C19.3137 6 22 8.6863 22 12C22 15.3137 19.3137 18 16 18H8C4.6863 18 2 15.3137 2 12C2 8.6863 4.6863 6 8 6Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wjbte45me {
  fill: currentColor;
  d: path("M11 12C11 13.6569 9.6569 15 8 15C6.3431 15 5 13.6569 5 12C5 10.3431 6.3431 9 8 9C9.6569 9 11 10.3431 11 12Z");
}

</style>
