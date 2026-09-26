<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3jqvyryi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-diagonal-sharp" /></template>
<style>
.e3jqvyryi {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.1339 2.5456L19.162 5.8195L9.514 20.6369C8.9604 21.4872 8.0146 22 7 22C5.3431 22 4 20.6569 4 19C4 18.4188 4.1688 17.8501 4.486 17.3631L14.1339 2.5456ZM13.0471 1.838L20.4544 6.661M7.3268 13L14.4866 13");
}

</style>
