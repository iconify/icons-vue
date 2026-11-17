<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fdl_phdii"/><path class="k_74-0epx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocking-horse-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fdl_phdii {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.051 16.684l1.869-5.607l-.367-.735l-1.106.552a1 1 0 0 1-1.341-.447l-1-2a1 1 0 0 1 0-.894l2-4A1 1 0 0 1 5 3a7.006 7.006 0 0 1 6.93 6H17c.446 0 .839.296.962.725l2 7a1 1 0 0 1-.348 1.064a12.3 12.3 0 0 1-4.351 2.176a1 1 0 0 1-1.233-.722L13.219 16h-2.438l-.811 3.243a1 1 0 0 1-1.233.722a12.3 12.3 0 0 1-4.351-2.176a1 1 0 0 1-.335-1.105");
}

.k_74-0epx {
  d: path("M18 11h-1a1 1 0 0 1 0-2h1a2 2 0 0 0 2-2a1 1 0 0 1 2 0a3.96 3.96 0 0 1-1.172 2.828A3.98 3.98 0 0 1 18 11m-9.26 8.966l-.003-.001a12.3 12.3 0 0 1-4.351-2.176a12.3 12.3 0 0 1-2.175-2.175a1 1 0 1 1 1.578-1.228a10.403 10.403 0 0 0 16.219.253q.103-.125.203-.253a1 1 0 1 1 1.578 1.228A12.4 12.4 0 0 1 8.74 19.966");
}

</style>
