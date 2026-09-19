<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG51ifd67j" class="wln8vzbzq"/></defs><use href="#SVG51ifd67j" class="pfsdhbbki"/><use href="#SVG51ifd67j" class="pfsdhbbki"/><path class="i7o939a4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-hourglass-top" /></template>
<style>
.i7o939a4z {
  fill: currentColor;
  d: path("M18 2H6v6l4 4l-3.99 4.01L6 22h12l-.01-5.99L14 12l4-3.99zm-2 14.5V20H8v-3.5l4-4zm0-9l-4 4l-4-4V4h8z");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wln8vzbzq {
  fill: currentColor;
  d: path("m8 7.5l4 4l4-4V4H8z");
}

</style>
