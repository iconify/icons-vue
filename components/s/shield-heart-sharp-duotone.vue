<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fvd42ib4r"/><path class="a0lz56b2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-heart-sharp-duotone" /></template>
<style>
.a0lz56b2j {
  d: path("M12 15.591C10.1796 14.0362 8.01 12.6983 8.01 10.7033C8.01 9.4361 9.0818 8.409 10.404 8.409C11.0025 8.409 11.5382 8.6268 12 9.0075C12.4618 8.6268 12.9975 8.409 13.596 8.409C14.9182 8.409 15.99 9.4361 15.99 10.7033C15.99 12.6983 13.8204 14.0362 12 15.591Z");
}

.fvd42ib4r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 5.3088L21 15.778C21 15.9994 20.9265 16.2146 20.7911 16.3897L19.4031 18.1846C18.148 19.8076 16.0328 21.7411 13.1746 22.7912C12.4724 23.0492 11.5276 23.0492 10.8253 22.7911C7.9672 21.7411 5.852 19.8076 4.5969 18.1846L3.2089 16.3895C3.0735 16.2143 3 15.9992 3 15.7778L3 5.3088C3 4.8021 3.379 4.3755 3.8821 4.3158L5.0646 4.1754C7.4767 3.8892 9.2001 2.7495 10.3279 1.6554C11.1316 0.8756 12.8684 0.8756 13.6721 1.6554C14.7999 2.7495 16.5233 3.8892 18.9353 4.1754L20.1179 4.3158C20.621 4.3755 21 4.8021 21 5.3088Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
