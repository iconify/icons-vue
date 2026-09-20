<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="hajjnez3d"/><path clip-rule="evenodd" class="dwv0fm5gm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sftmx-background" /></template>
<style>
.dwv0fm5gm {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 7.733l2.666 1.173v5.654L12 16.266L9.333 14.56V8.906zM9.866 9.536v1.749l1.584-.875zm1.867 1.322l-1.621.896l1.621 1.072zm.533 1.973l1.622-1.077l-1.622-.896zm1.867-.602L12 13.642L9.866 12.23v1.984L12 15.466l2.133-1.253zm0-.944l-1.584-.875l1.584-.874zm-.33-2.176L12 10.106l-1.803-.997l1.803-.8z");
}

.ft5dv1b6b {
  fill: none;
}

.hajjnez3d {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.61 4L4 7.61l1.547 1.291c.416-1.856 2.41-3.008 3.36-3.354L7.605 4zm8.518 0l-1.29 1.547c2.271 1.653 3.183 3.269 3.36 3.872L20 7.872zm0 15.744l-1.547-1.813c2.064-.41 3.094-2.576 3.355-3.611l1.808 1.813zm-6.71-1.29L7.873 20l-3.616-3.61l1.29-1.291c.827 2.064 2.929 3.093 3.873 3.354");
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
