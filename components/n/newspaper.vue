<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5akfjbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:newspaper" /></template>
<style>
.p5akfjbia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6C8 4.3431 9.3431 3 11 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 11C3 9.8954 3.8954 9 5 9L8 9L8 6ZM8 9L8 18C8 19.4639 6.9434 20.7141 5.5 20.958M12 8L17 8M12 12L17 12M12 16L15 16");
}

</style>
