<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1768obpb"/><path class="hi8a36bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-takeout-dining" /></template>
<style>
.hi8a36bia {
  fill: currentColor;
  d: path("M20.59 6.05L19 7.63l.03-.56L14.98 3H9.02L4.97 7.07l.03.5l-1.59-1.56L2 7.44l3.23 3.11l.7 9.45h12.14l.7-9.44L22 7.46zM16.23 18H7.79l-.51-7h9.46zm.64-9H7.12l-.09-1.27L9.83 5h4.33l2.8 2.73z");
}

.z1768obpb {
  fill: currentColor;
  d: path("m9.83 5l-2.8 2.73L7.12 9h9.75l.09-1.27L14.16 5zM7.79 18h8.44l.51-7H7.28z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
