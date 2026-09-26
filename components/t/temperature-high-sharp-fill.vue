<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dmbjsgbay"/><path class="cr_ndv8ed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-high-sharp-fill" /></template>
<style>
.cr_ndv8ed {
  d: path("M22 5C22 6.6569 20.6569 8 19 8C17.3431 8 16 6.6569 16 5C16 3.3431 17.3431 2 19 2C20.6569 2 22 3.3431 22 5Z");
}

.dmbjsgbay {
  fill: currentColor;
  d: path("M3 6C3 3.2386 5.2386 1 8 1C10.7614 1 13 3.2386 13 6L13 11.101C14.282 12.4094 15 14.1682 15 16C15 19.866 11.866 23 8 23C4.134 23 1 19.866 1 16C1 14.1682 1.718 12.4094 3 11.101L3 6ZM9 12.6459L9 6.5L7 6.5L7 12.6459C5.5167 13.0881 4.5 14.4522 4.5 16C4.5 17.933 6.067 19.5 8 19.5C9.933 19.5 11.5 17.933 11.5 16C11.5 14.4522 10.4833 13.0881 9 12.6459ZM9.5 16C9.5 16.8284 8.8284 17.5 8 17.5C7.1716 17.5 6.5 16.8284 6.5 16C6.5 15.1716 7.1716 14.5 8 14.5C8.8284 14.5 9.5 15.1716 9.5 16Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
