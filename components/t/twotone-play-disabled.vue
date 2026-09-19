<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oggi7oklw"/><path class="v159hid9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-play-disabled" /></template>
<style>
.oggi7oklw {
  fill: currentColor;
  d: path("M10 12.83v2.53l1.55-.99z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.v159hid9t {
  fill: currentColor;
  d: path("M2.81 2.81L1.39 4.22L8 10.83V19l4.99-3.18l6.78 6.78l1.41-1.41zM10 15.36v-2.53l1.55 1.55zM19 12L8 5v.17l8.45 8.45z");
}

</style>
