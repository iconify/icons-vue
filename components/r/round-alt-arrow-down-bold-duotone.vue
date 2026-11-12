<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghfixm1dc"/><path class="jq-gf3byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-down-bold-duotone" /></template>
<style>
.ghfixm1dc {
  fill: currentColor;
  d: path("M2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.jq-gf3byy {
  fill: currentColor;
  d: path("M15.5303 11.0303C15.8232 10.7374 15.8232 10.2626 15.5303 9.96967C15.2374 9.67678 14.7626 9.67678 14.4697 9.96967L12 12.4393L9.53033 9.96967C9.23744 9.67678 8.76256 9.67678 8.46967 9.96967C8.17678 10.2626 8.17678 10.7374 8.46967 11.0303L11.4697 14.0303C11.7626 14.3232 12.2374 14.3232 12.5303 14.0303L15.5303 11.0303Z");
}

</style>
