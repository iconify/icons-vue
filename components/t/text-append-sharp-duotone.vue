<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bbbjae6nq"/><path class="ilafzoavi"/><path class="v86mcuyzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-append-sharp-duotone" /></template>
<style>
.bbbjae6nq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 20V22H14V20H22ZM4 14V17.75H8.471L7.6 16.93L8.967 15.47L11.684 18.02C11.885 18.21 12 18.47 12 18.75C12 19.03 11.885 19.29 11.684 19.48L8.994 22L7.627 20.54L8.249 19.96L8.471 19.75H3C2.448 19.75 2 19.3 2 18.75V14H4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ilafzoavi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14V16H14V14H22ZM22 8V10H2V8H22ZM22 2V4H2V2H22Z");
}

.v86mcuyzm {
  d: path("M4 14V17.75H8.471L7.6 16.93L8.967 15.47L11.684 18.02C11.885 18.21 12 18.52 12 18.8C11.975 19.03 11.86 19.31 11.684 19.48L8.994 22L7.627 20.54L8.249 19.96L8.471 19.75H3C2.448 19.75 2 19.3 2 18.75V14H4Z");
}

</style>
