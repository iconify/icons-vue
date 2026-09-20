<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1FpA0bWI)" class="r4i437pya"/><path fill="url(#SVG3tq5KetE)" class="egahbqbmp"/><path fill="url(#SVGbMARJWzD)" clip-rule="evenodd" class="wtac8_bgw"/><path fill="url(#SVGOp5zWcAt)" clip-rule="evenodd" class="x8d86ci2w"/><path fill="url(#SVG69X1KblE)" class="d_2l2nd2c"/></g><defs><linearGradient id="SVG1FpA0bWI" x1="8.721" x2="19.846" y1="11.746" y2="14.778" gradientUnits="userSpaceOnUse"><stop class="q0dfisbly"/><stop offset="1" class="d4gvsjuxa"/></linearGradient><linearGradient id="SVG3tq5KetE" x1="8.721" x2="19.846" y1="11.746" y2="14.778" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGbMARJWzD" x1="17.92" x2="9.621" y1="11.527" y2="3.531" gradientUnits="userSpaceOnUse"><stop class="q0dfisbly"/><stop offset="1" class="wrzqkyhwx"/></linearGradient><linearGradient id="SVGOp5zWcAt" x1="13.799" x2="5.983" y1="16.184" y2="11.865" gradientUnits="userSpaceOnUse"><stop class="q0dfisbly"/><stop offset="1" class="wrzqkyhwx"/></linearGradient><linearGradient id="SVG69X1KblE" x1="9.382" x2="14.821" y1="11.66" y2="18.301" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".984" class="hllp4zbgf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rabby-background" /></template>
<style>
.d_2l2nd2c {
  d: path("M5.368 13.99c.19 1.688 1.113 2.35 2.997 2.545c1.884.196 2.964.065 4.403.201c1.202.114 2.275.751 2.673.53c.358-.197.157-.913-.322-1.372c-.621-.596-1.481-1.01-2.994-1.157c.301-.859.217-2.063-.251-2.719c-.678-.947-1.927-1.376-3.51-1.189c-1.652.196-3.235 1.043-2.996 3.161");
}

.d4gvsjuxa {
  stop-color: var(--svg-color--abb7ff, #abb7ff);
}

.egahbqbmp {
  d: path("M19.918 13.04c.629-1.461-2.478-5.543-5.446-7.243c-1.87-1.317-3.82-1.136-4.215-.558c-.866 1.27 2.869 2.345 5.367 3.6a2.9 2.9 0 0 0-1.34 1.235c-.932-1.058-2.976-1.969-5.375-1.235c-1.616.495-2.96 1.66-3.479 3.422a1 1 0 0 0-.412-.091c-.562 0-1.018.474-1.018 1.059s.456 1.059 1.018 1.059c.104 0 .43-.073.43-.073l5.204.04c-2.082 3.435-3.726 3.937-3.726 4.532s1.573.434 2.164.212c2.83-1.062 5.868-4.372 6.389-5.325c2.19.284 4.03.318 4.44-.634");
}

.ft5dv1b6b {
  fill: none;
}

.hllp4zbgf {
  stop-color: var(--svg-color--d1d8ff, #d1d8ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0dfisbly {
  stop-color: var(--svg-color--8697ff, #8697ff);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wrzqkyhwx {
  stop-color: var(--svg-color--8697ff, #8697ff);
  stop-opacity: 0;
}

.wtac8_bgw {
  fill-rule: evenodd;
  d: path("M15.624 8.839c.116-.048.097-.225.066-.365c-.073-.321-1.334-1.617-2.518-2.197c-1.614-.791-2.802-.75-2.978-.386c.329.701 1.853 1.36 3.444 2.047c.679.293 1.37.591 1.986.901");
}

.x8d86ci2w {
  fill-rule: evenodd;
  d: path("M13.576 15.894a9 9 0 0 0-1.114-.357c.447-.832.541-2.064.119-2.843c-.592-1.092-1.336-1.674-3.063-1.674c-.95 0-3.508.333-3.554 2.555q-.008.349.016.644l4.672.035a16.7 16.7 0 0 1-1.736 2.397c.62.165 1.131.304 1.601.431c.446.121.854.232 1.28.345a20 20 0 0 0 1.78-1.533");
}

</style>
