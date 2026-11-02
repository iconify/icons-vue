<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a9815muvx"/><path class="j1bdshiag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wheelchair-bulk-round" /></template>
<style>
.a9815muvx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.443 12.314a4.002 4.002 0 0 0 0 7.372A4 4 0 0 0 12.2 18.4a1 1 0 0 1 1.6 1.2A6 6 0 1 1 9 10a1 1 0 0 1 0 2a3.95 3.95 0 0 0-1.557.314");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j1bdshiag {
  d: path("M7.158 3.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558M10 9h4a1 1 0 0 1 0 2h-4v1a.997.997 0 0 0 1 1h3c1.348.001 2.357 1.478 2.894 2.553l1 2c.216.431.47.857.813 1.2c.093.093.2.197.324.247H20a1 1 0 0 1 0 2h-1c-1.348-.001-2.357-1.478-2.894-2.553l-1-2c-.216-.431-.47-.857-.813-1.2c-.093-.093-.2-.197-.324-.247H11a3 3 0 0 1-3-3V8a1 1 0 0 1 2 0Z");
}

</style>
