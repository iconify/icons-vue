<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z96-wb2ae"/><path class="tt-ip7t0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:questlab" /></template>
<style>
.tt-ip7t0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.369 11.123c-3.864.012-7.995 1.885-11.178 5.069c-5.654 5.654-6.742 13.734-2.43 18.046c3.613 3.611 10.001 3.503 15.448-.261l-5.008-4.836h9.826c3.72-5.436 3.807-11.785.211-15.38c-1.719-1.718-4.133-2.646-6.87-2.638");
}

.z96-wb2ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.126 2.5 2.5 12.126 2.5 24a21.5 21.5 0 0 0 2.502 10.066c-2.133-6.91.657-15.623 7.049-22.015S27.156 2.869 34.066 5A21.5 21.5 0 0 0 24 2.5m18.998 11.434c1.84 5.96.03 13.343-4.764 19.441v.002l3.194 3.215a21.5 21.5 0 0 0 1.57-22.658M33.51 38.129c-6.12 4.87-13.57 6.724-19.576 4.869a21.5 21.5 0 0 0 22.847-1.709z");
}

</style>
