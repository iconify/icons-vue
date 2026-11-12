<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="uhl-u5b-k"/><path class="jutrygoyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-right-bold-duotone" /></template>
<style>
.jutrygoyf {
  fill: currentColor;
  d: path("M13.0303 15.5303C12.7374 15.8232 12.2626 15.8232 11.9697 15.5303C11.6768 15.2374 11.6768 14.7626 11.9697 14.4697L14.4393 12L11.9697 9.53033C11.6768 9.23744 11.6768 8.76256 11.9697 8.46967C12.2626 8.17678 12.7374 8.17678 13.0303 8.46967L16.0303 11.4697C16.3232 11.7626 16.3232 12.2374 16.0303 12.5303L13.0303 15.5303Z");
}

.uhl-u5b-k {
  fill: currentColor;
  d: path("M9.03033 15.5303C8.73744 15.8232 8.26256 15.8232 7.96967 15.5303C7.67678 15.2374 7.67678 14.7626 7.96967 14.4697L10.4393 12L7.96967 9.53033C7.67678 9.23744 7.67678 8.76256 7.96967 8.46967C8.26256 8.17678 8.73744 8.17678 9.03033 8.46967L12.0303 11.4697C12.3232 11.7626 12.3232 12.2374 12.0303 12.5303L9.03033 15.5303Z");
}

.xrdvcwidb {
  fill: currentColor;
  d: path("M2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
