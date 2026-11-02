<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z_mysib1j"/><path class="o4qyerm4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o4qyerm4y {
  d: path("M15.707 8.293L18 10.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L19.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414L18 13.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L16.586 12l-2.293-2.293a.999.999 0 1 1 1.414-1.414");
}

.z_mysib1j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6v12c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C6.98 17.395 6.468 17 6 17H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l2-2c.31-.311.752-.456 1.186-.382C11.428 4.072 12 5.102 12 6");
}

</style>
