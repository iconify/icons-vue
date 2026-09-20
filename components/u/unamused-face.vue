<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p1xtd6blu"/><g class="ehej3-bmx"><path class="epen8go7x"/><path class="q_y1sk8up"/><path class="o35d3lbhz"/><path class="y82w8jb8v"/><path class="vmwu2ojxr"/></g><path class="mo8h-cbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:unamused-face" /></template>
<style>
.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.epen8go7x {
  d: path("M56.64 56.12c0 .03-.01.06-.01.09c0-.03 0-.06.01-.09m-15.98-3.53H29.42c-1.66 0-3 1.34-3 3s1.34 3 3 3h11.81c-.46-1.2-.72-2.52-.73-3.91c-.02-.72.04-1.42.16-2.09");
}

.mo8h-cbdv {
  fill: none;
  stroke: var(--svg-color--2f2f2f, #2f2f2f);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M50.02 85.11c7.34-6.96 20.62-6.96 27.95 0");
}

.o35d3lbhz {
  d: path("M56.63 56.2c0-.03.01-.06.01-.09a2.996 2.996 0 0 0-2.95-3.53H40.66c-.12.67-.18 1.37-.17 2.09c.01 1.4.28 2.72.73 3.91h12.47c1.45.01 2.66-1.01 2.94-2.38m44.9-.08c0 .03-.01.06-.01.09c.01-.03 0-.06.01-.09m-15.98-3.53H74.31c-1.66 0-3 1.34-3 3s1.34 3 3 3h11.81c-.46-1.2-.72-2.52-.73-3.91c-.02-.72.05-1.42.16-2.09");
}

.p1xtd6blu {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 9.9C1.99 9.9.51 79.42.51 93.19c0 13.76 28.43 24.91 63.49 24.91c35.07 0 63.49-11.16 63.49-24.91c0-13.77-1.47-83.29-63.49-83.29");
}

.q_y1sk8up {
  d: path("M53.69 58.59H41.22c1.29 3.39 4.17 5.74 7.48 5.7c4.01-.04 7.3-3.53 7.92-8.09a2.975 2.975 0 0 1-2.93 2.39");
}

.vmwu2ojxr {
  d: path("M101.52 56.2c0-.03.01-.06.01-.09a2.996 2.996 0 0 0-2.95-3.53H85.55c-.12.67-.18 1.37-.17 2.09c.01 1.4.28 2.72.73 3.91h12.47c1.45.01 2.66-1.01 2.94-2.38");
}

.y82w8jb8v {
  d: path("M98.58 58.59H86.11c1.29 3.39 4.17 5.74 7.48 5.7c4.01-.04 7.3-3.53 7.92-8.09a2.975 2.975 0 0 1-2.93 2.39");
}

</style>
