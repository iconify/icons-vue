<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i4-t51yxh"/><path class="y__xrubmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocking-chair-two-tone" /></template>
<style>
.i4-t51yxh {
  d: path("M4 3L6.7862 12.2873C6.9131 12.7103 7.3024 13 7.744 13H10M14 13H17M14 13L17 20.1107M14 13H10M10 13L7 20.1107");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y__xrubmn {
  stroke-opacity: 0.4;
  d: path("M22 17C20.5505 18.3805 18.8454 19.4327 17 20.1107C15.4127 20.6938 13.7216 21 12 21C10.2784 21 8.58726 20.6938 7 20.1107C5.15456 19.4327 3.44949 18.3805 2 17");
}

</style>
