<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="my-cvcb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-clock-fill" /></template>
<style>
.my-cvcb7w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C17.8553 2 23 5.8327 23 11C23 16.1673 17.8553 20 12 20C11.2351 20 10.4723 19.9337 9.7236 19.8047L5.4385 21.8984C5.1434 22.0425 4.7961 22.0329 4.5098 21.8721C4.2235 21.7112 4.0344 21.4197 4.0039 21.0928L3.6084 16.8252C1.9521 15.2269 1 13.1718 1 11C1 5.8327 6.1447 2 12 2ZM13 7C13 6.4477 12.5523 6 12 6C11.4477 6 11 6.4477 11 7L11 11C11 11.5523 11.4477 12 12 12L15 12C15.5523 12 16 11.5523 16 11C16 10.4477 15.5523 10 15 10L13 10Z");
}

</style>
