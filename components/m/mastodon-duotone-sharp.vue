<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wc7o1vb4o"/><path class="snjmdcbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mastodon-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.snjmdcbst {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 13V9a2 2 0 1 1 4 0v2m0-2a2 2 0 1 1 4 0v4m2.65 2.25C16.83 17.02 12 17 12 17H9c.84 1.61 3.83 2.43 8.69 2.1c-1.94 2.01-13.59 5.26-13.66-7.64L4 10.31c0-3.04.02-4.12 1.35-5.63C7.02 3 12 3 12 3s4.98 0 6.65 1.68C19.98 6.2 20 7.27 20 10.31s-.46 4.07-1.35 4.94");
}

.wc7o1vb4o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.877 17.972c1.553.259 3.179.236 4.745.13a1.001 1.001 0 0 1 .788 1.692c-.399.413-.901.718-1.408.976c-.635.317-1.299.572-1.983.761c-3.525.995-7.531.535-9.892-2.544c-1.625-2.124-2.082-4.911-2.097-7.522L3 10.336v-.026c0-.663-.002-1.328.025-1.991c.043-1.048.174-2.071.667-3.013a6.5 6.5 0 0 1 .949-1.331c1.1-1.105 3.03-1.54 4.517-1.755A22 22 0 0 1 12 2q.43.003.857.028q.997.051 1.985.192c1.487.215 3.417.65 4.517 1.755l.044.046c.346.396.661.823.905 1.289c.492.942.624 1.963.667 3.011c.027.662.025 1.326.025 1.989q0 2.307-.384 3.574a4.74 4.74 0 0 1-1.267 2.081l-.002.002c-1.15 1.117-3.019 1.579-4.555 1.811q-.953.141-1.915.194");
}

</style>
