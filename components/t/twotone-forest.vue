<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oel92qgar"/><path class="rglo-m2bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-forest" /></template>
<style>
.oel92qgar {
  fill: currentColor;
  d: path("M16.48 10h1.68L15 5.49l-1.78 2.54L16 12h-1.86l2.57 4h3.63zm-4.32 0L9 5.49L5.84 10h1.68l-3.86 6h10.68l-3.86-6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rglo-m2bg {
  fill: currentColor;
  d: path("M20.14 12H22L15 2l-3 4.29L9 2L2 12h1.86L0 18h7v4h4v-4h2v4h4v-4h7zM3.66 16l3.86-6H5.84L9 5.49L12.16 10h-1.68l3.86 6zm13.05 0l-2.57-4H16l-2.78-3.97L15 5.49L18.16 10h-1.68l3.86 6z");
}

</style>
