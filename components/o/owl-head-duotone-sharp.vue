<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e3xvw3b-s"/><path class="oolx8wghy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-head-duotone-sharp" /></template>
<style>
.e3xvw3b-s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.168 4.316c2.409.917 5.255.917 7.664 0c1.289-.492 2.469-1.238 3.543-2.097a1 1 0 0 1 1.553.41c.522 1.304.809 2.693.942 4.089C22.006 8.14 22 9.572 22 11a11.8 11.8 0 0 1-.768 4.237C19.758 19.123 16.254 21.999 12 22a9.14 9.14 0 0 1-3.942-.884A9.9 9.9 0 0 1 4.88 18.73C2.987 16.618 2 13.825 2 11c0-.729 0-1.458.016-2.187q.02-1.049.114-2.095c.133-1.396.42-2.785.942-4.089a.998.998 0 0 1 1.553-.41c1.074.859 2.254 1.605 3.543 2.097");
}

.ft5dv1b6b {
  fill: none;
}

.oolx8wghy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3c2.5 2 5 3 8 3s5.5-1 8-3c1 2.5 1 5 1 8c0 5.5-4 10-9 10s-9-4.5-9-10c0-3 0-5.5 1-8m2 8a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m-3 4h2l-1 2Z");
}

</style>
