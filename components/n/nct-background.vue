<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iyfax81qg"/><path class="fkmag6raf"/><path class="q9hgi6r_n"/><path class="g7o-ryysk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nct-background" /></template>
<style>
.fkmag6raf {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.642 8h8.544C15.43 8 16.5 9.27 16.5 10.5S15.43 13 14.186 13H9.458c-.354 0-.67.15-.67.5s.316.5.67.5h4.5c1.953 0 3.542-1.57 3.542-3.5S15.91 7 13.958 7H5.643C5.288 7 5 7.15 5 7.5s.288.5.642.5");
}

.ft5dv1b6b {
  fill: none;
}

.g7o-ryysk {
  fill: var(--svg-color--fff, #fff);
  d: path("M10 10.5c0-.333-.218-.5-.56-.5H8.07c-.34 0-.57.167-.57.5c0 .335.248.5.474.5h1.397c.434 0 .629-.145.629-.5m-1.615 8H4.618c-.34 0-.618.167-.618.5s.277.5.618.5h3.767c.34 0 .615-.167.615-.5s-.274-.5-.615-.5");
}

.iyfax81qg {
  fill: var(--svg-color--8500ff, #8500ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9hgi6r_n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.742 4.5h-3.105c-.34 0-.637.165-.637.498s.296.502.637.502h3.105C16.51 5.5 19 7.907 19 10.61c0 2.702-2.49 4.89-5.258 4.89H5.855c-.34 0-.618.166-.618.5s.277.5.618.5h7.886c3.451 0 6.259-2.522 6.259-5.89c0-3.37-2.808-6.11-6.258-6.11");
}

</style>
