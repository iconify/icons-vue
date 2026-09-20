<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="znjh2jbiv"/><g class="n1mjunbsu"><path class="r32zpxf7k"/><ellipse class="lp6bfwb0h"/><path class="nw163mbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:new-moon-face" /></template>
<style>
.lp6bfwb0h {
  cx: 37.51px;
  cy: 58.24px;
  rx: 7.22px;
  ry: 7.95px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nw163mbpa {
  d: path("M83.04 58.24c0 4.39 3.24 7.96 7.23 7.96c3.97 0 7.2-3.57 7.2-7.96s-3.23-7.95-7.2-7.95c-3.99 0-7.23 3.56-7.23 7.95M71.4 75.08c-2.35-1.16-2.58 3.06-7.38 3.06c-2.8 0-6.26-1.96-6.19-5.07c.01-.57.02-1.1.16-1.66c.16-.63.38-1.19.61-1.8c.43-1.17.98-2.29 1.49-3.42c.4-.89.75-1.81 1.04-2.74c1.35-4.37 1.4-9.12-1.11-13.18c-.32-.53-.62-1.12-1.1-1.49c-1.6-1.24-2.58.26-2.32 1.72c.38 2.18 1.67 4.01 1.89 6.27c.33 3.35-.61 7.12-2.25 10.08c-.23.41-.5.84-.7 1.27c-1.07 2.32-1.86 5.03-.87 7.57c1.38 3.54 5.69 5.75 9.34 5.75c6.28.01 9.74-5.2 7.39-6.36");
}

.r32zpxf7k {
  d: path("M65.27 95.48c-3.48.04-7.01-.73-9.87-2.15c-1.43-.71-2.92-1.69-4.06-2.8c-1.15-1.12-2.26-3.13-.91-4.5c1.09-1.11 2.71.01 3.76.58c2.99 1.63 6.4 2.83 9.86 2.98c3.83.17 6.94-1 10.23-2.74c.95-.5 2.82-1.72 3.92-1.04c2.76 1.67-.52 4.68-1.93 5.88c-3.05 2.57-6.97 3.75-11 3.79");
}

.znjh2jbiv {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 .4C28.88.4.41 28.88.4 64c.01 35.12 28.47 63.59 63.6 63.6c35.12 0 63.59-28.47 63.59-63.6S99.12.4 64 .4");
}

</style>
