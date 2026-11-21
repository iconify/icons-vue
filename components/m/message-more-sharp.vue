<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vezgql98p"/><path class="jif2u-bco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-more-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jif2u-bco {
  fill: currentColor;
  d: path("M8.5 11C8.5 11.8285 7.8285 12.5 7 12.5C6.1716 12.5 5.5 11.8285 5.5 11C5.5 10.1716 6.1716 9.5 7 9.5C7.8285 9.5 8.5 10.1716 8.5 11ZM13.5 11C13.5 11.8285 12.8285 12.5 12 12.5C11.1716 12.5 10.5 11.8285 10.5 11C10.5 10.1716 11.1716 9.5 12 9.5C12.8285 9.5 13.5 10.1716 13.5 11ZM18.5 11C18.5 11.8285 17.8285 12.5 17 12.5C16.1716 12.5 15.5 11.8285 15.5 11C15.5 10.1716 16.1716 9.5 17 9.5C17.8285 9.5 18.5 10.1716 18.5 11Z");
  stroke: none;
}

.vezgql98p {
  d: path("M4.5686 16.353C2.915 14.8839 2 12.9769 2 11C2 6.5817 6.4772 3 12 3C17.5228 3 22 6.5817 22 11C22 15.4183 17.5228 19 12 19C11.1845 19 10.3721 18.9202 9.5808 18.7624L5 21Z");
}

</style>
