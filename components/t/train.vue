<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y27fy8gkp"/><defs><path id="SVGkU4FJdrv" class="nnruox1go"/></defs><use href="#SVGkU4FJdrv" class="j71m3fb1u"/><path class="r2_pbi8rl"/><path class="mh38gac4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:train" /></template>
<style>
.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.mh38gac4i {
  fill: var(--svg-color--fff, #fff);
  d: path("M40.05 87.78c0 4.64-3.77 8.4-8.41 8.4c-4.65 0-8.42-3.76-8.42-8.4a8.42 8.42 0 0 1 8.42-8.42c4.64 0 8.41 3.77 8.41 8.42m47.91 0c0 4.64 3.76 8.4 8.41 8.4c4.64 0 8.4-3.76 8.4-8.4c0-4.65-3.76-8.42-8.4-8.42c-4.65 0-8.41 3.77-8.41 8.42");
}

.nnruox1go {
  d: path("M115.23 87.76c0 12.81-10.38 23.18-23.18 23.18h-56.1c-12.79 0-23.19-10.38-23.19-23.18V23.9C12.76 11.09 23.15.72 35.95.72h56.1c12.81 0 23.18 10.38 23.18 23.18z");
}

.r2_pbi8rl {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M105.01 36.75c0 6.9-5.58 12.5-12.5 12.5H35.5c-6.9 0-12.5-5.6-12.5-12.5V20.94c0-6.9 5.6-12.49 12.5-12.49h57.01c6.92 0 12.5 5.59 12.5 12.49z");
}

.y27fy8gkp {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M43.57 122.22a5.06 5.06 0 0 1-5.06 5.06c-2.78 0-5.04-2.27-5.04-5.06V102.8c0-2.78 2.26-5.05 5.04-5.05c2.8 0 5.06 2.27 5.06 5.05zm40.87 0c0 2.79 2.26 5.06 5.05 5.06s5.05-2.27 5.05-5.06V102.8c0-2.78-2.26-5.05-5.05-5.05s-5.05 2.27-5.05 5.05z");
}

</style>
