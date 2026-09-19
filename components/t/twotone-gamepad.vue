<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nes-m6bmm"/><path class="y39h2gbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-gamepad" /></template>
<style>
.nes-m6bmm {
  fill: currentColor;
  d: path("M6.67 11H4v2h2.67l1-1zM13 6.67V4h-2v2.67l1 1zm-2 10.66V20h2v-2.67l-1-1zM16.33 12l1 1H20v-2h-2.67z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y39h2gbmb {
  fill: currentColor;
  d: path("M9 16.5V22h6v-5.5l-3-3zm4 3.5h-2v-2.67l1-1l1 1zm2-12.5V2H9v5.5l3 3zM11 4h2v2.67l-1 1l-1-1zM7.5 9H2v6h5.5l3-3zm-.83 4H4v-2h2.67l1 1zm9.83-4l-3 3l3 3H22V9zm3.5 4h-2.67l-1-1l1-1H20z");
}

</style>
