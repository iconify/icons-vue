<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qbn2fdbay"/><path class="zq3qi-bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-off-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbn2fdbay {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.659 15.659L9.8877 20.3316C9.3536 20.7641 8.6872 21 8 21C6.3431 21 5 19.6569 5 18L5 6C5 5.705 5.0435 5.4115 5.1292 5.1292ZM12.9846 8.7419C12.797 8.5544 12.6917 8.3 12.6917 8.0348C12.6917 7.4825 13.1394 7.0348 13.6917 7.0348C13.9208 7.0348 14.1429 7.1135 14.3209 7.2576L18.2585 10.4456C18.7275 10.8253 19 11.3965 19 12C19 12.202 18.9694 12.4028 18.9093 12.5956C18.779 13.0133 18.3922 13.2978 17.9546 13.2978C17.6894 13.2978 17.4351 13.1924 17.2475 13.0049L12.9846 8.7419Z");
  stroke: none;
}

.zq3qi-bml {
  d: path("M14.948 14.948L9.2585 19.5544C8.9024 19.8427 8.4582 20 8 20C6.8954 20 6 19.1046 6 18L6 6M2 2L22 22");
}

</style>
