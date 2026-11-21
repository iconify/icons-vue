<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a8tq3acmj"/><path class="ycv65ab_p"/><path class="u0mhz-bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-bug-sharp-duotone" /></template>
<style>
.a8tq3acmj {
  stroke-opacity: 0.4;
  d: path("M10 9L10 8L10 2.0024L21.9991 10L17 14.5252L16.6711 14.8229");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0mhz-bhz {
  d: path("M4.3222 14.7586C3.3469 14.5603 2.6111 13.658 2.6111 12.5575L2.6111 12L2.6111 11M10.6778 14.7586C11.6531 14.5603 12.3889 13.658 12.3889 12.5575L12.3889 12L12.3889 11M13 23L13 22L13 21.4425C13 20.3994 12.0412 19.5443 10.7695 19.3563L10.4587 19.3103M2 23L2 21.4425C2 20.3994 2.9594 19.5443 4.2305 19.3563L4.5413 19.3103");
}

.ycv65ab_p {
  fill: currentColor;
  d: path("M4.4346 20.7424C3.6434 19.9847 3.1389 18.9249 3.1389 17.7471L3.1389 15.6207C3.1389 15.2264 3.2215 14.7916 3.402 14.3673C3.4456 14.2645 3.5062 14.1698 3.5812 14.0871C4.5716 12.9942 6.0064 12.3793 7.5 12.3793C8.9936 12.3793 10.4284 12.9942 11.4188 14.0871C11.4938 14.1698 11.5544 14.2645 11.598 14.3673C11.7785 14.7916 11.8611 15.2264 11.8611 15.6207L11.8611 17.7471C11.8611 18.9249 11.3566 19.9847 10.5654 20.7424C9.7747 21.4994 8.6884 21.9655 7.5 21.9655C6.3116 21.9655 5.2253 21.4994 4.4346 20.7424Z");
  stroke: none;
}

</style>
