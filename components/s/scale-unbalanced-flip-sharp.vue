<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzs9g5q7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scale-unbalanced-flip-sharp" /></template>
<style>
.jzs9g5q7w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12.8573L19 7.178L16 12.8573C18.1133 14.0457 19.8867 14.0457 22 12.8573ZM8 16.3573L5 10.678L2 16.3573C4.1133 17.5457 5.8867 17.5457 8 16.3573ZM10 4C10 5.1046 10.8954 6 12 6C13.1046 6 14 5.1046 14 4C14 2.8954 13.1046 2 12 2C10.8954 2 10 2.8954 10 4ZM9.9385 4.5202C9.3223 5.4604 6.5241 7.2809 4.1322 6.0323L3.595 5.7518M13.8094 3.5121C14.806 4.0324 18.1368 4.2567 19.6158 2L19.9119 1.5482M12 6L12 22M18 22L6 22");
}

</style>
