<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q34ia8-ee"/><path class="nixwj9ael"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:neutral-face" /></template>
<style>
.nixwj9ael {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M42.21 62.3c-4.49.04-8.17-4.27-8.22-9.62c-.05-5.37 3.55-9.75 8.04-9.79c4.48-.04 8.17 4.27 8.22 9.64c.05 5.35-3.55 9.72-8.04 9.77m44.11 0c4.48-.01 8.11-4.36 8.1-9.71c-.01-5.37-3.66-9.7-8.14-9.69c-4.49.01-8.13 4.36-8.12 9.73c.02 5.35 3.67 9.68 8.16 9.67m3.37 22.45H38.31c-1.66 0-3-1.34-3-3s1.34-3 3-3H89.7c1.66 0 3 1.34 3 3s-1.35 3-3.01 3");
}

.q34ia8-ee {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 9.56C1.59 9.56.12 79.52.12 93.36c0 13.86 28.59 25.08 63.88 25.08c35.28 0 63.88-11.22 63.88-25.08c0-13.84-1.48-83.8-63.88-83.8");
}

</style>
