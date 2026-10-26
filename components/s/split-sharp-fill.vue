<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs5n11bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:split-sharp-fill" /></template>
<style>
.vs5n11bss {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 22L12 13L6 13L6 3M12 13L18 13L18 3M2.7071 6.2929L6 3L9.2929 6.2929M14.7071 6.2929L18 3L21.2929 6.2929");
}

</style>
