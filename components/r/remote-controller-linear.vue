<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="icfn4znuq"/><path class="iqy4f3ajf"/><path class="s3rslbcfp"/><path class="zwiw2-bkv"/><path class="g3w7qrfpr"/><path class="ca53wpbej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-linear" /></template>
<style>
.ca53wpbej {
  stroke-linejoin: round;
  d: path("M12 9H12.0001");
}

.g3w7qrfpr {
  stroke-linejoin: round;
  d: path("M15 9H15.0001");
}

.icfn4znuq {
  d: path("M12 22C9.19108 22 7.78661 22 6.77772 21.3259C6.34096 21.034 5.96596 20.659 5.67412 20.2223C5 19.2134 5 17.8089 5 15V9C5 6.19108 5 4.78661 5.67412 3.77772C5.96596 3.34096 6.34096 2.96596 6.77772 2.67412C7.78661 2 9.19108 2 12 2C14.8089 2 16.2134 2 17.2223 2.67412C17.659 2.96596 18.034 3.34096 18.3259 3.77772C19 4.78661 19 6.19108 19 9V15C19 17.8089 19 19.2134 18.3259 20.2223C18.034 20.659 17.659 21.034 17.2223 21.3259C16.2134 22 14.8089 22 12 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqy4f3ajf {
  d: path("M15 15.5C15 17.1569 13.6569 18.5 12 18.5C10.3431 18.5 9 17.1569 9 15.5C9 13.8431 10.3431 12.5 12 12.5C13.6569 12.5 15 13.8431 15 15.5Z");
}

.s3rslbcfp {
  d: path("M9 5.5H15");
}

.zwiw2-bkv {
  stroke-linejoin: round;
  d: path("M9 9H9.0001");
}

</style>
