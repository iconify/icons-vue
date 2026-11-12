<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4erfbgl"/><path class="o8houvrgo"/><path class="mijy_4gbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-left-bold-duotone" /></template>
<style>
.gt4erfbgl {
  fill: currentColor;
  d: path("M22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mijy_4gbi {
  fill: currentColor;
  d: path("M10.9697 15.5303C11.2626 15.8232 11.7374 15.8232 12.0303 15.5303C12.3232 15.2374 12.3232 14.7626 12.0303 14.4697L9.56066 12L12.0303 9.53033C12.3232 9.23744 12.3232 8.76256 12.0303 8.46967C11.7374 8.17678 11.2626 8.17678 10.9697 8.46967L7.96967 11.4697C7.67678 11.7626 7.67678 12.2374 7.96967 12.5303L10.9697 15.5303Z");
}

.o8houvrgo {
  fill: currentColor;
  d: path("M14.9697 15.5303C15.2626 15.8232 15.7374 15.8232 16.0303 15.5303C16.3232 15.2374 16.3232 14.7626 16.0303 14.4697L13.5607 12L16.0303 9.53033C16.3232 9.23744 16.3232 8.76256 16.0303 8.46967C15.7374 8.17678 15.2626 8.17678 14.9697 8.46967L11.9697 11.4697C11.6768 11.7626 11.6768 12.2374 11.9697 12.5303L14.9697 15.5303Z");
}

</style>
