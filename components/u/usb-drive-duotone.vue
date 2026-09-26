<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g1tghbccd"/><path clip-rule="evenodd" class="ox-5v-b6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb-drive-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g1tghbccd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L12 3C13.2713 3 14.4046 3.8014 14.8284 5L20 5C21.6569 5 23 6.3431 23 8L23 16C23 17.6569 21.6569 19 20 19L14.8284 19C14.4046 20.1986 13.2713 21 12 21L4 21C2.3431 21 1 19.6569 1 18L1 6C1 4.3431 2.3431 3 4 3Z");
}

.ox-5v-b6k {
  fill-rule: evenodd;
  d: path("M4 3L12 3C13.6569 3 15 4.3431 15 6L15 18C15 19.6569 13.6569 21 12 21L4 21C2.3431 21 1 19.6569 1 18L1 6C1 4.3431 2.3431 3 4 3ZM19 10C19 10.5523 18.5523 11 18 11C17.4477 11 17 10.5523 17 10C17 9.4477 17.4477 9 18 9C18.5523 9 19 9.4477 19 10ZM19 14C19 14.5523 18.5523 15 18 15C17.4477 15 17 14.5523 17 14C17 13.4477 17.4477 13 18 13C18.5523 13 19 13.4477 19 14Z");
}

</style>
