<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGWUWv3EhZ"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="jnz2dqb7s"/><path class="eb6ve5l2b"/></g></mask></defs><circle mask="url(#SVGWUWv3EhZ)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-camera-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.eb6ve5l2b {
  d: path("M9.5 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.ft5dv1b6b {
  fill: none;
}

.jnz2dqb7s {
  d: path("M8.696 8.078L8.398 9H7.5a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h11a3 3 0 0 0 3-3v-6a3 3 0 0 0-3-3h-.899l-.297-.922A3 3 0 0 0 14.449 6H11.55a3 3 0 0 0-2.855 2.078M7.5 11h2.354l.745-2.307A1 1 0 0 1 11.551 8h2.898a1 1 0 0 1 .951.693L16.145 11H18.5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

</style>
