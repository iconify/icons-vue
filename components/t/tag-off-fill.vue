<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ovjx23bbz"/><path class="rsrhfac5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-off-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ovjx23bbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.293 17.707L10.707 22.121C11.879 23.293 13.778 23.293 14.95 22.121L22.121 14.95C23.293 13.778 23.293 11.879 22.121 10.707L17.707 6.293L6.293 17.707ZM14.879 3.464L13.293 1.879C12.73 1.316 11.967 1 11.172 1H5C2.791 1 1 2.791 1 5V11.172C1 11.967 1.316 12.73 1.879 13.293L3.464 14.879C3.645 15.06 3.895 15.172 4.172 15.172C4.448 15.172 4.698 15.06 4.879 14.879L14.879 4.879C15.06 4.698 15.172 4.448 15.172 4.172C15.172 3.895 15.06 3.645 14.879 3.464ZM9.5 8C9.5 8.828 8.828 9.5 8 9.5C7.172 9.5 6.5 8.828 6.5 8C6.5 7.172 7.172 6.5 8 6.5C8.828 6.5 9.5 7.172 9.5 8Z");
  stroke: none;
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

</style>
