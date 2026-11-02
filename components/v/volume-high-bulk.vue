<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z_mysib1j"/><path class="a8luhacgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-bulk" /></template>
<style>
.a8luhacgk {
  d: path("M18.789 4.386a12.395 12.395 0 0 1 0 15.228a1 1 0 1 1-1.578-1.228a10.3 10.3 0 0 0 1.643-3.052c.364-1.074.549-2.2.548-3.334a10.4 10.4 0 0 0-.548-3.334a10.3 10.3 0 0 0-1.643-3.052a.999.999 0 1 1 1.578-1.228m-2.957 3.059a8.21 8.21 0 0 1 0 9.11a1 1 0 1 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1.002 1.002 0 0 1 .638-1.536c.397-.078.802.09 1.026.426");
}

.cuyn6tgcc {
  fill: currentColor;
}

.z_mysib1j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6v12c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C6.98 17.395 6.468 17 6 17H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l2-2c.31-.311.752-.456 1.186-.382C11.428 4.072 12 5.102 12 6");
}

</style>
