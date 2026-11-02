<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="amcv3fb9n"/><path class="waezl2blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snail-bulk-round" /></template>
<style>
.amcv3fb9n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 20v-8a7 7 0 0 1 6.498-6.982A7.003 7.003 0 0 1 15.93 11H19a1 1 0 0 1 1 1v5c0 2.248-1.752 4-4 4H3a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.waezl2blu {
  d: path("M20 17c0 2.248-1.752 4-4 4H3a1 1 0 0 1 0-2h13c1.145 0 2-.855 2-2V8.236l-1.894-3.789a1 1 0 0 1 .954-1.445a1 1 0 0 1 .834.551L19 5.764l1.106-2.211a1 1 0 1 1 1.788.894L20 8.236Zm-4-5a5 5 0 0 1-10 0a2.999 2.999 0 0 1 5.121-2.121c.564.563.88 1.324.879 2.121a1 1 0 0 1-2 0a1.002 1.002 0 0 0-1.707-.707A1 1 0 0 0 8 12a2.98 2.98 0 0 0 .879 2.121A3.002 3.002 0 0 0 14 12a1 1 0 0 1 2 0");
}

</style>
