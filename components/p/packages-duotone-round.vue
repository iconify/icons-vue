<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="at111kbdg"/><path class="xh6wvxbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:packages-duotone-round" /></template>
<style>
.at111kbdg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16.5 10.875l3.394 1.697A2 2 0 0 1 21 14.361v3.153a2 2 0 0 1-1.106 1.789l-2.5 1.25a2 2 0 0 1-1.788 0L12 18.75l-3.606 1.803a2 2 0 0 1-1.788 0l-2.5-1.25A2 2 0 0 1 3 17.514v-3.153a2 2 0 0 1 1.106-1.789L7.5 10.875V6.486a2 2 0 0 1 1.106-1.789l2.5-1.25a2 2 0 0 1 1.788 0l2.5 1.25A2 2 0 0 1 16.5 6.486Z");
}

.ft5dv1b6b {
  fill: none;
}

.xh6wvxbvp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16.5 10.875l3.394 1.697A2 2 0 0 1 21 14.362v3.152a2 2 0 0 1-1.106 1.789l-2.5 1.25a2 2 0 0 1-1.788 0L12 18.75l-3.606 1.803a2 2 0 0 1-1.788 0l-2.5-1.25A2 2 0 0 1 3 17.513v-3.152a2 2 0 0 1 1.106-1.789L7.5 10.875V6.486a2 2 0 0 1 1.106-1.789l2.5-1.25a2 2 0 0 1 1.788 0l2.5 1.25a2 2 0 0 1 1.106 1.79zM7.816 5.408L12 7.5l4.184-2.092M12 7.5v5.625m-4.5-2.25l4.5 2.25l4.5-2.25M3.316 13.283L7.5 15.375l4.5-2.25l4.5 2.25l4.184-2.092M7.5 15.375v5.389m4.5-7.639v5.625m4.5-3.375v5.389");
}

</style>
