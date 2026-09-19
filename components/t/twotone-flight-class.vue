<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgizw2ptg"/><path class="uzb9s4b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-flight-class" /></template>
<style>
.tgizw2ptg {
  fill: currentColor;
  d: path("M14 6h2v5h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.uzb9s4b6i {
  fill: currentColor;
  d: path("M16 4h-2c-1.1 0-2 .9-2 2v5c0 1.1.9 2 2 2h2c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 7h-2V6h2zm-6.5 5H18v2H9.49c-.88 0-1.66-.58-1.92-1.43L5 8V4h2v4zM8 19h10v2H8z");
}

</style>
