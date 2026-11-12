<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk06ssbdv"/><path class="ho54-sbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toggle-right-bold-duotone" /></template>
<style>
.ho54-sbmt {
  fill: currentColor;
  d: path("M19 12C19 13.6569 17.6569 15 16 15C14.3431 15 13 13.6569 13 12C13 10.3431 14.3431 9 16 9C17.6569 9 19 10.3431 19 12Z");
}

.pk06ssbdv {
  fill: currentColor;
  d: path("M8 6H16C19.3137 6 22 8.6863 22 12C22 15.3137 19.3137 18 16 18H8C4.6863 18 2 15.3137 2 12C2 8.6863 4.6863 6 8 6Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
