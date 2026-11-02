<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lnwupqbzi"/><path class="wpn6sw86c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-medium-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lnwupqbzi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 19h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

.wpn6sw86c {
  d: path("M13 8a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0Zm-4 4a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0Zm-4 4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Z");
}

</style>
