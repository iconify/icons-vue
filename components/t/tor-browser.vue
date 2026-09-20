<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGSYAajeNN" x1="50%" x2="50%" y1="100%" y2="0%"><stop offset="0%" class="euezyny1x"/><stop offset="100%" class="sci2_fjrw"/></linearGradient></defs><circle class="z0d5_ibur"/><path fill="url(#SVGSYAajeNN)" class="s4euzls6s"/><path fill="url(#SVGSYAajeNN)" transform="matrix(-1 0 0 1 140.5 0)" class="sq1tfvhki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tor-browser" /></template>
<style>
.euezyny1x {
  stop-color: var(--svg-color--420c5d, #420c5d);
}

.s4euzls6s {
  d: path("M128.263 232.72v-15.517c49.15-.142 88.947-40.02 88.947-89.207c0-49.182-39.797-89.06-88.947-89.203V23.277c57.72.145 104.46 46.968 104.46 104.72c0 57.755-46.74 104.58-104.46 104.723m0-54.31c27.722-.145 50.161-22.652 50.161-50.414c0-27.758-22.439-50.264-50.161-50.41V62.073c36.295.142 65.678 29.596 65.678 65.923c0 36.331-29.383 65.785-65.678 65.927zm0-77.55c14.87.141 26.888 12.23 26.888 27.136c0 14.91-12.018 27-26.888 27.141zM0 127.995C0 198.692 57.304 256 128 256c70.692 0 128-57.308 128-128.004C256 57.304 198.692 0 128 0C57.304 0 0 57.304 0 127.996");
}

.sci2_fjrw {
  stop-color: var(--svg-color--951ad1, #951ad1);
}

.sq1tfvhki {
  d: path("M12.5 14.5c63.789 0 115.5 51.487 115.5 115s-51.711 115-115.5 115z");
}

.z0d5_ibur {
  cx: 128px;
  cy: 128px;
  r: 123px;
  fill: var(--svg-color--f2e4ff, #f2e4ff);
}

</style>
