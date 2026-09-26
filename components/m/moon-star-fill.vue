<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="btis9lbsd"/><path class="q41if-b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-star-fill" /></template>
<style>
.btis9lbsd {
  fill: currentColor;
  d: path("M21 13C21 18.5228 16.5228 23 11 23C5.4772 23 1 18.5228 1 13C1 7.4772 5.4772 3 11 3C11.3844 3 11.7348 3.2203 11.9013 3.5668C12.0678 3.9133 12.021 4.3245 11.7809 4.6247C10.061 6.7746 10.2326 9.8738 12.1794 11.8206C14.1262 13.7674 17.2254 13.939 19.3753 12.2191C19.6755 11.979 20.0867 11.9322 20.4332 12.0987C20.7797 12.2652 21 12.6156 21 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q41if-b8j {
  d: path("M18.9689 2L18.9689 9M15.9378 3.75L22 7.25M22 3.75L15.9378 7.25");
}

</style>
