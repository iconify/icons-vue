<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="j-5gudbub"/><path class="rimuh7bpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-x-fill" /></template>
<style>
.j-5gudbub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 11C20 15.9706 15.9706 20 11 20C6.0294 20 2 15.9706 2 11C2 6.0294 6.0294 2 11 2C15.9706 2 20 6.0294 20 11ZM12.4142 11L13.8284 12.4142C14.016 12.6017 14.1213 12.8561 14.1213 13.1213C14.1213 13.6736 13.6736 14.1213 13.1213 14.1213C12.8561 14.1213 12.6017 14.016 12.4142 13.8284L11 12.4142L9.5858 13.8284C9.3983 14.016 9.1439 14.1213 8.8787 14.1213C8.3264 14.1213 7.8787 13.6736 7.8787 13.1213C7.8787 12.8561 7.984 12.6017 8.1716 12.4142L9.5858 11L8.1716 9.5858C7.984 9.3983 7.8787 9.1439 7.8787 8.8787C7.8787 8.3264 8.3264 7.8787 8.8787 7.8787C9.1439 7.8787 9.3983 7.984 9.5858 8.1716L11 9.5858L12.4142 8.1716C12.6017 7.984 12.8561 7.8787 13.1213 7.8787C13.6736 7.8787 14.1213 8.3264 14.1213 8.8787C14.1213 9.1439 14.016 9.3983 13.8284 9.5858L12.4142 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rimuh7bpm {
  d: path("M17 17L21 21");
}

</style>
