<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngwru8-xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-sharp" /></template>
<style>
.ngwru8-xt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 14L18 14L22 22L2 22ZM10 14L8.6667 22M14 14L15.3333 22M4 18L20 18M7.6933 10.5556L7.9689 10C8.7286 8.4686 10.2905 7.5 12 7.5C13.7095 7.5 15.2714 8.4686 16.0311 10L16.3067 10.5556M12 4.5L12 1M17.7175 6.2825L19.364 4.636M6.2825 6.2825L4.636 4.636M4.4689 10L1.4689 10M19.5311 10L22.5311 10");
}

</style>
