<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eur9f7bvf"/><path class="t6vkiswyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-send" /></template>
<style>
.eur9f7bvf {
  fill: currentColor;
  d: path("m4 8.25l7.51 1l-7.5-3.22zm.01 9.72l7.5-3.22l-7.51 1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t6vkiswyc {
  fill: currentColor;
  d: path("M2.01 3L2 10l15 2l-15 2l.01 7L23 12zM4 8.25V6.03l7.51 3.22zm.01 9.72v-2.22l7.51-1z");
}

</style>
