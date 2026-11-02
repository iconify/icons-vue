<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ytyn1kb9c"/><path class="a14vpk97p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-duotone-sharp" /></template>
<style>
.a14vpk97p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v9m-4 0h8M12 8V3c1.5 1 2 3 1.41 5.59Zm1.732 3l4.33 2.5c-1.616.799-3.598.232-5.546-1.574Zm-3.464 0l-4.33 2.5c.116-1.799 1.598-3.232 4.136-4.016Z");
}

.ft5dv1b6b {
  fill: none;
}

.ytyn1kb9c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 3a1 1 0 0 1 1.555-.832c.981.654 1.618 1.652 1.904 2.787c.317 1.264.213 2.598-.074 3.857a1 1 0 0 1-1.361.7l-1.41-.59A1 1 0 0 1 11 8ZM6.438 14.366a1 1 0 0 1-1.498-.93c.076-1.177.621-2.228 1.461-3.042c.936-.908 2.144-1.484 3.378-1.866a1 1 0 0 1 1.287.829l.194 1.516a1 1 0 0 1-.492.993Zm12.124-1.732a1 1 0 0 1-.057 1.762c-1.057.523-2.239.576-3.365.256c-1.254-.357-2.356-1.115-3.304-1.993a1 1 0 0 1 .074-1.528l1.216-.927a1 1 0 0 1 1.106-.07Z");
}

</style>
