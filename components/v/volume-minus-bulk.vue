<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z_mysib1j"/><path class="gi76mbcrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-minus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gi76mbcrc {
  d: path("M15 11h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

.z_mysib1j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6v12c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C6.98 17.395 6.468 17 6 17H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l2-2c.31-.311.752-.456 1.186-.382C11.428 4.072 12 5.102 12 6");
}

</style>
