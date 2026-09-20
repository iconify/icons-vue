<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pryvj3bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-32-regular" /></template>
<style>
.pryvj3bjp {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14c0 3.453-1.481 6.364-3.075 8.5a21.5 21.5 0 0 1-3.306 3.5H29a1 1 0 1 1 0 2h-6.345a1.655 1.655 0 0 1-1.646-1.486l-.009-.17l.012-.2c.055-.46.3-.87.659-1.143a19.4 19.4 0 0 0 3.651-3.697C26.767 21.367 28 18.87 28 16c0-6.627-5.373-12-12-12S4 9.373 4 16c0 2.87 1.233 5.367 2.678 7.304A19.4 19.4 0 0 0 10.329 27c.411.312.671.803.671 1.344C11 29.259 10.259 30 9.345 30H3a1 1 0 1 1 0-2h5.38a21.5 21.5 0 0 1-3.305-3.5C3.481 22.364 2 19.453 2 16C2 8.268 8.268 2 16 2");
}

</style>
