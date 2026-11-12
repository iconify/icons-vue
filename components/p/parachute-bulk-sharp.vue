<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hdqvxsm1n"/><path class="lz150fv8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parachute-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hdqvxsm1n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9c0-1.105.275-2.194.847-3.142c.553-.914 1.348-1.652 2.254-2.21C7.12 2.406 9.662 2 12 2s4.88.406 6.899 1.648c.906.558 1.701 1.296 2.254 2.21C21.725 6.806 22 7.895 22 9a1 1 0 0 1-1.555.832C19.274 9.052 17.924 8.5 16.5 8.5s-2.774.552-3.945 1.332a1 1 0 0 1-1.11 0C10.274 9.052 8.924 8.5 7.5 8.5s-2.774.552-3.945 1.332A1 1 0 0 1 2 9");
}

.lz150fv8d {
  d: path("M11 15.586V9a1 1 0 0 1 2 0v6.586l7.293-7.293a.999.999 0 1 1 1.414 1.414L13 18.414V20h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2h2v-1.586L2.293 9.707a.999.999 0 1 1 1.414-1.414Z");
}

</style>
