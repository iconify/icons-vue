<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbk45fb1a"/><path class="wy4wumbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-two-tone" /></template>
<style>
.lbk45fb1a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C12.3844 2 12.7348 2.2203 12.9013 2.5668C13.0678 2.9133 13.021 3.3245 12.7809 3.6247C11.061 5.7746 11.2326 8.8738 13.1794 10.8206C15.1262 12.7674 18.2254 12.939 20.3753 11.2191C20.6755 10.979 21.0867 10.9322 21.4332 11.0987C21.7797 11.2652 22 11.6156 22 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wy4wumbry {
  d: path("M21 12C21 16.9706 16.9706 21 12 21C7.0294 21 3 16.9706 3 12C3 7.0294 7.0294 3 12 3C9.9618 5.5477 10.1652 9.2206 12.4723 11.5277C14.7794 13.8348 18.4523 14.0382 21 12Z");
}

</style>
