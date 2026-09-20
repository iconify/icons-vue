<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pu8mb4b4f"/><path class="bvcoddcbd"/><path class="bcpzwpbor"/><path class="sgi8qwmdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:pill" /></template>
<style>
.bcpzwpbor {
  fill: var(--svg-color--c62828, #c62828);
  d: path("m86.818 45.424l-41.401 41.4l-2.122-2.12l41.401-41.402z");
}

.bvcoddcbd {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("M84.7 43.3L53.94 12.54c-11.38-11.38-30.01-11.38-41.4 0c-11.38 11.38-11.38 30.01 0 41.4L43.3 84.7z");
}

.pu8mb4b4f {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M74.06 115.46c11.38 11.38 30.01 11.38 41.4 0c11.38-11.38 11.38-30.01 0-41.4L84.7 43.3L43.3 84.7z");
}

.sgi8qwmdm {
  fill: var(--svg-color--fff, #fff);
  d: path("M69.43 36.25C81.59 49.5 103.65 74.5 103.65 74.5c2.86 2.61 6.79 9.34 4.22 11.66c-2.74 2.48-9.12-2.75-11.98-5.36L49.22 36.89c-2.85-2.61-12.39-11.06-10.53-17.01c3.51-11.23 17.2 1.61 30.74 16.37");
  opacity: var(--svg-opacity--0-65, 0.65);
}

</style>
