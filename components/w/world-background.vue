<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="hsaywzx1a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:world-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hsaywzx1a {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.011 5.07A7.84 7.84 0 0 0 12 4a7.84 7.84 0 0 0-4.011 1.07a8 8 0 0 0-2.92 2.919A7.84 7.84 0 0 0 4 12q0 2.173 1.07 4.011a8 8 0 0 0 2.919 2.92A7.84 7.84 0 0 0 12 20a7.84 7.84 0 0 0 4.011-1.07a8 8 0 0 0 2.92-2.919A7.84 7.84 0 0 0 20 12a7.84 7.84 0 0 0-1.07-4.011a8 8 0 0 0-2.919-2.92m-3.52 9.827c-.914 0-1.627-.268-2.185-.78a2.44 2.44 0 0 1-.735-1.293h8.646a6.6 6.6 0 0 1-.624 2.073zm-2.92-3.7c.111-.49.357-.935.735-1.292c.558-.512 1.27-.78 2.184-.78h5.103a6 6 0 0 1 .624 2.073zM6.585 8.814a6.24 6.24 0 0 1 2.273-2.295a6.17 6.17 0 0 1 3.164-.847c1.16 0 2.206.29 3.165.847c.49.29.913.624 1.314 1.025h-4.033c-.914 0-1.738.2-2.451.58a4.03 4.03 0 0 0-1.65 1.582a4.6 4.6 0 0 0-.534 1.515H5.85a6 6 0 0 1 .78-2.384zm8.58 8.669A6.17 6.17 0 0 1 12 18.33a6.17 6.17 0 0 1-3.164-.847a6.24 6.24 0 0 1-2.273-2.295a5.9 5.9 0 0 1-.78-2.362h1.983c.09.534.267 1.047.535 1.515c.4.668.958 1.18 1.649 1.582c.713.379 1.538.58 2.451.58h4.011a6 6 0 0 1-1.27.98z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
