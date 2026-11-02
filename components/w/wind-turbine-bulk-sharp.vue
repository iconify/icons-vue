<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zg4o6gakp"/><path class="j0vdsabou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j0vdsabou {
  d: path("M11 8V3a1 1 0 0 1 1.555-.832c.981.654 1.618 1.652 1.904 2.787c.317 1.264.213 2.598-.074 3.857a1 1 0 0 1-1.361.7l-1.41-.59A1 1 0 0 1 11 8m-.232 3.866l-4.33 2.5a1 1 0 0 1-1.498-.93c.076-1.177.621-2.228 1.461-3.042c.936-.908 2.144-1.484 3.378-1.866a1 1 0 0 1 1.287.829l.194 1.516a1 1 0 0 1-.492.993m3.464-1.732l4.33 2.5a1 1 0 0 1-.057 1.762c-1.867.923-3.875.344-5.505-.792V20h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3v-8a1 1 0 0 1 1.078-.997l1.048-.799a1 1 0 0 1 1.106-.07");
}

.zg4o6gakp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 7.171V3a1 1 0 0 1 1.555-.832c.981.654 1.618 1.652 1.904 2.787c.276 1.1.232 2.257.028 3.365c.441.653.608 1.454.463 2.229l3.612 2.085a1 1 0 0 1-.057 1.762c-1.057.523-2.239.576-3.365.256c-1.091-.311-2.071-.928-2.929-1.659a3 3 0 0 1-2.161-.713l-3.612 2.086a1 1 0 0 1-1.498-.93c.076-1.177.621-2.228 1.461-3.042c.815-.79 1.839-1.33 2.901-1.708A3 3 0 0 1 11 7.171");
}

</style>
