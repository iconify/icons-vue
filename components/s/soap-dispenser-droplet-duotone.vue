<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cat0s5bsl"/><path clip-rule="evenodd" class="wol-zlblj"/><path class="j11d2zbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:soap-dispenser-droplet-duotone" /></template>
<style>
.cat0s5bsl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.1674 23L7 23C4.7908 23 3 21.2092 3 19L3 14C3 11.7908 4.7908 10 7 10L13 10C13.9165 9.9989 14.8053 10.3136 15.517 10.8911C14.8934 11.1257 14.3498 11.5336 13.95 12.0667L11.75 15C10.9386 16.0818 10.4999 17.3977 10.4999 18.75C10.4999 20.3263 11.0955 21.8443 12.1674 23Z");
  stroke: none;
}

.j11d2zbus {
  d: path("M10 2L10 7M7 2L11.1716 2C12.9826 2 14.7194 2.7194 16 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wol-zlblj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 11L6 7.5C6 6.6716 6.6716 6 7.5 6L12.5 6C13.3284 6 14 6.6716 14 7.5L14 11C14 11.5523 13.5523 12 13 12L7 12C6.4477 12 6 11.5523 6 11ZM20.15 16.2C20.7018 16.9357 21 17.8304 21 18.75C21 21.0972 19.0972 23 16.75 23C14.4028 23 12.5 21.0972 12.5 18.75C12.5 17.8304 12.7983 16.9357 13.35 16.2L15.55 13.2667C15.8333 12.889 16.2779 12.6667 16.75 12.6667C17.2221 12.6667 17.6667 12.889 17.95 13.2667L20.15 16.2Z");
  stroke: none;
}

</style>
