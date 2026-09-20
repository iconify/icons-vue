<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG0p1iZc4t" class="soh5v2bjb"/></defs><path class="ztksxgbzl"/><path class="p98g6dbye"/><use href="#SVG0p1iZc4t" class="k0jpwu2hx"/><use href="#SVG0p1iZc4t" class="e0ty9gbgt"/><path class="s53h1vbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sparkle" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.k0jpwu2hx {
  opacity: var(--svg-opacity--0-35, 0.35);
}

.p98g6dbye {
  fill: var(--svg-color--7cb342, #7cb342);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c0 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.s53h1vbdj {
  fill: var(--svg-color--fff, #fff);
  d: path("m93.94 52.66l16.33 6.04c1.62.6 1.62 2.9 0 3.5l-16.33 6.04A37.46 37.46 0 0 0 71.8 90.38l-6.04 16.33c-.6 1.62-2.9 1.62-3.5 0l-6.04-16.33a37.46 37.46 0 0 0-22.14-22.14L17.75 62.2c-1.62-.6-1.62-2.9 0-3.5l16.33-6.04a37.46 37.46 0 0 0 22.14-22.14l6.04-16.33c.6-1.62 2.9-1.62 3.5 0l6.04 16.33a37.46 37.46 0 0 0 22.14 22.14");
}

.soh5v2bjb {
  fill: var(--svg-color--abc884, #abc884);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
}

.ztksxgbzl {
  fill: var(--svg-color--689f38, #689f38);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

</style>
