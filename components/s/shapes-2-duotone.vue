<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ko45wjbye"/><path class="dl3qxj56t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-2-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dl3qxj56t {
  d: path("M9.3182 3.6589C10.4236 1.447 13.5801 1.447 14.6854 3.6589L16.1835 6.657C17.1798 8.6515 15.7295 10.9978 13.4999 10.9978L10.5038 10.9978C8.274 10.9978 6.8236 8.6516 7.8202 6.657L9.3182 3.6589Z");
}

.ko45wjbye {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.5 13C8.9853 13 11 15.0147 11 17.5C11 19.9853 8.9853 22 6.5 22C4.0147 22 2 19.9853 2 17.5C2 15.0147 4.0147 13 6.5 13ZM19 13C20.6569 13 22 14.3431 22 16L22 19C22 20.6569 20.6569 22 19 22L16 22C14.3431 22 13 20.6569 13 19L13 16C13 14.3431 14.3431 13 16 13L19 13Z");
}

</style>
