<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="advb3y65b"/><path class="g2mcemujw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:satellite-dish-sharp-duotone" /></template>
<style>
.advb3y65b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.571 8.0154C3.7586 7.8278 4.0129 7.7225 4.2781 7.7225C4.5433 7.7225 4.7977 7.8279 4.9852 8.0154L15.9846 19.0148C16.1721 19.2023 16.2775 19.4567 16.2775 19.7219C16.2775 19.9871 16.1722 20.2414 15.9846 20.429C14.3378 22.0754 12.1046 23.0003 9.7759 23.0003C8.3373 23.0003 6.9207 22.6468 5.6506 21.971C2.7875 20.4461 0.999 17.4661 1 14.2222C1 11.8942 1.9248 9.6615 3.571 8.0154Z");
  stroke: none;
}

.g2mcemujw {
  d: path("M9.7778 14.2222L12.2929 11.7071M12.1111 6.4444L13.1111 6.4444C15.5657 6.4444 17.5556 8.4343 17.5556 10.8889L17.5556 11.8889M12.1111 2L13.1111 2C18.0203 2 22 5.9797 22 10.8889L22 11.8889");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
