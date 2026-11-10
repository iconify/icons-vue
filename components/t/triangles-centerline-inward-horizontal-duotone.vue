<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c536gvbkn"/><path class="e-xjv8bxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-inward-horizontal-duotone" /></template>
<style>
.c536gvbkn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.0001 15C12.2118 15 12.7048 15.2 12.923 15.32L16.7862 21.05C16.7871 21.05 16.7882 21.05 16.7891 21.05C17.0881 21.5 17.0469 22.04 16.7911 22.42C16.5453 22.79 16.1298 23 15.6983 23H8.3018C7.8698 23 7.4533 22.79 7.2071 22.42C6.95 22.04 6.9105 21.5 7.213 21.05L10.958 15.5C11.2346 15.19 11.6812 15 12.0001 15ZM15.6983 1C16.1298 1 16.5454 1.21 16.7911 1.58C17.0474 1.96 17.0882 2.5 16.7872 2.95L13.0899 8.43C12.8111 8.84 12.3649 9 12.0001 9C11.7209 9 11.2683 8.8 11.0056 8.57L7.213 2.95C6.9105 2.5 6.95 1.96 7.2071 1.58C7.4533 1.21 7.8698 1 8.3018 1H15.6983Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.e-xjv8bxe {
  d: path("M22 11C22.5523 11 23 11.45 23 12C23 12.55 22.5523 13 22 13H2C1.4477 13 1 12.55 1 12C1 11.45 1.4477 11 2 11H22Z");
}

</style>
