<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="plc69ledh"/><path class="ksho03byu"/><path class="ro3t6fcmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reindeer-sharp" /></template>
<style>
.ksho03byu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.2 11.25l-2.676-.765L4.2 12.25l1.85 1.11l2.15-.86Zm7.6 0l2.676-.765L19.8 12.25l-1.85 1.11l-2.15-.86Z");
}

.plc69ledh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9c2.5 0 4 1.75 4 4.5c0 3.5-2 7.75-4 7.75S8 17 8 13.5C8 10.75 9.5 9 12 9Zm-2 .25L8.643 6.536L5.5 5.75m2.1.75l.15-3.75m-2.25 3L3 3.5m11 5.75l1.357-2.714L18.5 5.75m-2.1.75l-.15-3.75m2.25 3L21 3.5");
}

.ro3t6fcmg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 13h.01m2.99 0h.01M12 17h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
