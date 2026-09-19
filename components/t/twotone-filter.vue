<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oclmyxbtu"/><path class="luckh9b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter" /></template>
<style>
.luckh9b7v {
  fill: currentColor;
  d: path("M1 21c0 1.1.9 2 2 2h16v-2H3V5H1zM21 1H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14zm-5.04-6.71l-2.75 3.54l-1.96-2.36L8.5 15h11z");
}

.oclmyxbtu {
  fill: currentColor;
  d: path("M7 17h14V3H7zm4.25-5.53l1.96 2.36l2.75-3.54L19.5 15h-11z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
