<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bjfdbpbey"/><path fill="url(#SVGdKxyAehE)" class="lpfi0cb1g"/><path fill="url(#SVGt6ks481z)" class="hs4r6acot"/><defs><linearGradient id="SVGdKxyAehE" x1="15.346" x2="7.139" y1="7.762" y2="13.96" gradientUnits="userSpaceOnUse"><stop offset=".09" class="jnslgigxl"/><stop offset=".5" class="nbn9c3hhe"/><stop offset="1" class="nbn9c3hhe"/></linearGradient><linearGradient id="SVGt6ks481z" x1="13.561" x2="6.954" y1="4.951" y2="11.42" gradientUnits="userSpaceOnUse"><stop class="jn-c9kuep"/><stop offset=".07" class="vftx4acjl"/><stop offset=".19" class="f5yz3cbda"/><stop offset=".3" class="rjjsysb6b"/><stop offset=".4" class="it_5nyksi"/><stop offset=".49" class="e7z87gbgy"/><stop offset=".55" class="rcp0509is"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nftx" /></template>
<style>
.bjfdbpbey {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.826 15.612c.15-.209.292-.407.463-.6c-2.05.513-3.46 1.589-3.46 2.833q0 .07.006.14q.3-.12.638-.29c1.354-.692 1.884-1.431 2.353-2.083M10.96 17.9c.41-.57.763-1.063 1.764-1.573c1-.511 1.59-.502 2.275-.49c.46.007.953.015 1.557-.12c-.736-.411-1.944-.722-3.013-.888l-1.628 1.186l-.74-.722c-.772.54-1.167 1.09-1.526 1.588c-.41.57-.764 1.063-1.764 1.574c-.702.358-1.202.46-1.674.486c.373.514 1 .965 1.803 1.312q.282-.112.592-.271c1.354-.69 1.885-1.43 2.354-2.082m6.198-1.477c-.782-.013-1.669-.027-3.022.664c-1.354.692-1.884 1.431-2.353 2.083c-.41.57-.764 1.063-1.764 1.574l-.133.066a11.6 11.6 0 0 0 2.578.181c.25-.275.446-.546.63-.802c.41-.57.764-1.064 1.764-1.574s1.591-.501 2.275-.49c.315.005.648.01 1.02-.03q.02-.124.019-.249c0-.51-.238-.993-.66-1.42zm-2.684 4.313c1.617-.362 2.872-1.069 3.41-1.938c-.462.088-.988.257-1.614.577c-.873.446-1.404.912-1.796 1.36");
}

.e7z87gbgy {
  stop-color: var(--svg-color--652cb4, #652cb4);
  stop-opacity: 0.04;
}

.f5yz3cbda {
  stop-color: var(--svg-color--652cb4, #652cb4);
  stop-opacity: 0.53;
}

.ft5dv1b6b {
  fill: none;
}

.hs4r6acot {
  d: path("M12 10.2H5.057L12 3z");
}

.it_5nyksi {
  stop-color: var(--svg-color--652cb4, #652cb4);
  stop-opacity: 0.14;
}

.jn-c9kuep {
  stop-color: var(--svg-color--652cb4, #652cb4);
}

.jnslgigxl {
  stop-color: var(--svg-color--ff6d41, #ff6d41);
}

.lpfi0cb1g {
  d: path("m12 3l-6.943 7.2L12 16.886l6.943-6.686z");
}

.nbn9c3hhe {
  stop-color: var(--svg-color--fa297f, #fa297f);
}

.rcp0509is {
  stop-color: var(--svg-color--652cb4, #652cb4);
  stop-opacity: 0;
}

.rjjsysb6b {
  stop-color: var(--svg-color--652cb4, #652cb4);
  stop-opacity: 0.3;
}

.vftx4acjl {
  stop-color: var(--svg-color--652cb4, #652cb4);
  stop-opacity: 0.82;
}

</style>
