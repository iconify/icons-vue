<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v9csvhbaz"/><defs><path id="SVGQDNTieXk" class="c5if4kb5d"/></defs><use href="#SVGQDNTieXk" class="j71m3fb1u"/><path class="oskr7bg8r"/><path class="ujg33ibwc"/><path class="icifdtyqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:oncoming-bus" /></template>
<style>
.c5if4kb5d {
  d: path("M113.87 17.12c-.11-2.13-1.57-4.97-3.24-6.3c0 0-12.97-10.37-47.3-10.37S17.27 10.69 17.27 10.69c-1.61 1.41-3.02 4.31-3.13 6.44l-2.72 50.76c-.11 2.14-.21 5.63-.21 7.77v31.77a3.9 3.9 0 0 0 3.89 3.89h97.82a3.9 3.9 0 0 0 3.89-3.89V75.64c0-2.14-.09-5.63-.21-7.77z");
}

.icifdtyqo {
  fill: var(--svg-color--fff, #fff);
  d: path("M88.25 18.63H38.38c-2.4 0-4.36-1.95-4.36-4.36s1.96-4.36 4.36-4.36h49.87c2.41 0 4.35 1.95 4.35 4.36a4.343 4.343 0 0 1-4.35 4.36");
}

.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.oskr7bg8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M35.75 92.4c0 4.07-3.32 7.39-7.4 7.39c-4.09 0-7.39-3.32-7.39-7.39c0-4.08 3.31-7.39 7.39-7.39c4.09 0 7.4 3.31 7.4 7.39m56.98 0c0 4.07 3.31 7.39 7.4 7.39c4.08 0 7.39-3.32 7.39-7.39c0-4.08-3.31-7.39-7.39-7.39c-4.09 0-7.4 3.31-7.4 7.39");
}

.ujg33ibwc {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M105.91 32.33c-.11-4.27-3.71-7.77-7.98-7.77H30.08c-4.28 0-7.87 3.5-7.98 7.77l-.87 32.45a7.553 7.553 0 0 0 7.57 7.77h70.43c4.28 0 7.68-3.5 7.57-7.77z");
}

.v9csvhbaz {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M93.44 120.95c0 3.64 2.95 6.6 6.59 6.6s6.59-2.96 6.59-6.6V94.23c0-3.63-2.95-6.59-6.59-6.59s-6.59 2.96-6.59 6.59zm-58.88 0c0 3.64-2.95 6.6-6.59 6.6s-6.59-2.96-6.59-6.6V94.23c0-3.63 2.95-6.59 6.59-6.59s6.59 2.96 6.59 6.59z");
}

</style>
