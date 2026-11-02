<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z_mysib1j"/><path class="qmk-fqbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-low-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qmk-fqbto {
  d: path("M16.866 9.644c.23.764.345 1.558.345 2.356s-.115 1.592-.345 2.356a8.2 8.2 0 0 1-1.034 2.199a1 1 0 0 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1 1 0 0 1 .277-1.387a1 1 0 0 1 1.387.277a8.2 8.2 0 0 1 1.034 2.199");
}

.z_mysib1j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6v12c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C6.98 17.395 6.468 17 6 17H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l2-2c.31-.311.752-.456 1.186-.382C11.428 4.072 12 5.102 12 6");
}

</style>
