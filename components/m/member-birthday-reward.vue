<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j7hl3nb_e"/><path class="wk9_vqmqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:member-birthday-reward" /></template>
<style>
.j7hl3nb_e {
  d: path("M12.7 21.5H3.5V11h12.6m3.3 0h.1v.3M10.75 6h2.5v5h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wk9_vqmqz {
  d: path("M3.5 14.5c1.5 1.5 3-1 4.5 0c.235.156.457.227.671.241m1.486-.505c.387-.183.778-.312 1.202-.165M12 2.5c.75.75 1 1.25 0 2c-1-.75-.75-1.25 0-2ZM17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
