<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c99f33b4l"/><path class="fa4mqyvho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:motorbike-bulk-sharp" /></template>
<style>
.c99f33b4l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 9h1a3 3 0 0 1 3 3v1a.998.998 0 0 1-1.196.981l-5-1A1 1 0 0 1 8 12a3 3 0 0 1 .236-1.168c.15-.357.369-.68.643-.953A3 3 0 0 1 11 9m-8.685 7.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m12 0a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114M5 18a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fa4mqyvho {
  d: path("M17 13a3.99 3.99 0 0 0-3.2 1.6l-.001.001A4.03 4.03 0 0 0 13 17q0 .147-.021.294A2 2 0 0 1 11 19H9.874a4 4 0 1 1 0-2H11c0-1.705.73-3.337 2-4.475V12a.997.997 0 0 0-1-1h-1a.997.997 0 0 0-1 1a1 1 0 0 1-1.316.949l-6-2a1.001 1.001 0 0 1 .632-1.898l4.846 1.615l.024.009l.105.035A3 3 0 0 1 11 9h1c1.411 0 2.633.987 2.933 2.366A5.9 5.9 0 0 1 17 11V8a1 1 0 0 0-1-1a.997.997 0 0 1-1-1a.997.997 0 0 1 1-1a2.98 2.98 0 0 1 2.121.879c.566.565.882 1.322.879 2.121v6.126a4 4 0 1 1-2 0ZM4.157 18.778a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556m15.686-1.556a2 2 0 1 0-3.686 1.556a2 2 0 0 0 3.686-1.556");
}

</style>
