<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_l3fw_0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sharp" /></template>
<style>
.y_l3fw_0j {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.4645 3L21 6.5355L6.5355 21L3 17.4645L17.4645 3ZM13.1251 7.3393L16.6607 10.8749");
}

</style>
