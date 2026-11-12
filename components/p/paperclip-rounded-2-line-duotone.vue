<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="okgs1pb0k"/><path class="cbjl0_2fs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-line-duotone" /></template>
<style>
.cbjl0_2fs {
  d: path("M4.13095 18.3247C1.28968 15.4963 1.28968 10.9106 4.13095 8.08229L7.80563 4.4243C11.0528 1.1919 16.3175 1.1919 19.5646 4.4243");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okgs1pb0k {
  d: path("M12.9502 11.0087L10.0104 13.9351C8.38687 15.5513 8.38687 18.1716 10.0104 19.7878C11.634 21.4041 14.2664 21.4041 15.8899 19.7878L19.5646 16.1299C22.8118 12.8975 22.8118 7.6567 19.5646 4.4243C16.3175 1.1919 11.0528 1.1919 7.80563 4.4243L4.13095 8.08229C1.28968 10.9106 1.28968 15.4963 4.13095 18.3247");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
