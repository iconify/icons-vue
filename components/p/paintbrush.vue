<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asg9s5bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paintbrush" /></template>
<style>
.asg9s5bxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L16 2C17.1046 2 18 2.8954 18 4L18 11.5C18 11.7761 18.2239 12 18.5 12C18.7761 12 19 12.2239 19 12.5L19 13C19 14.6569 17.6569 16 16 16L15.6297 16C14.6831 16 13.9732 16.866 14.1588 17.7942L14.5 19.5C14.5 20.8807 13.3807 22 12 22C10.6193 22 9.5 20.8807 9.5 19.5L9.8412 17.7942C10.0268 16.866 9.3169 16 8.3703 16L8 16C6.3431 16 5 14.6569 5 13L5 12.5C5 12.2239 5.2239 12 5.5 12C5.7761 12 6 11.7761 6 11.5L6 4C6 2.8954 6.8954 2 8 2ZM6 12L18 12M10 2L10 6M14 2L14 8");
}

</style>
