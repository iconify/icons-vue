<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t6glvcbxk"/><path clip-rule="evenodd" class="cy6ta2bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ruler-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cy6ta2bws {
  fill-rule: evenodd;
  d: path("M6.343 13.414L9.172 16.243L7.757 17.657L4.929 14.828L6.343 13.414ZM9.172 10.586L10.939 12.354L9.525 13.768L7.757 12L9.172 10.586ZM12 7.757L14.828 10.586L13.414 12L10.586 9.172L12 7.757ZM14.828 4.929L16.596 6.697L15.182 8.111L13.414 6.343L14.828 4.929Z");
}

.t6glvcbxk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.293 17.05C1.105 16.863 1 16.608 1 16.343C1 16.078 1.105 15.824 1.293 15.636L15.636 1.293C15.824 1.105 16.078 1 16.343 1C16.608 1 16.863 1.105 17.05 1.293L22.707 6.95C22.895 7.137 23 7.392 23 7.657C23 7.922 22.895 8.176 22.707 8.364L8.364 22.707C8.176 22.895 7.922 23 7.657 23C7.392 23 7.137 22.895 6.95 22.707L1.293 17.05Z");
}

</style>
