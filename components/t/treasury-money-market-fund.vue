<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q73g-z-mt"/><path class="nspxuibym"/><path class="gwd5fxbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-money-market-fund" /></template>
<style>
.gwd5fxbkp {
  d: path("M13 7c0-.42-.43-.62-1-.5c-.7-.12-1.12.22-1 .75c-.12 1.05 2.12.6 2 2c.12.5-.35.87-1 .75c-.6.12-1.03-.12-1-.5m1-3.75v.75m0 3.5v.75m-8.25.5a2 .75 0 1 0 4 0a2 .75 0 1 0-4 0Zm12.5 0a2 .75 0 1 0 4 0a2 .75 0 1 0-4 0Zm-7.75 4l.25 3.5m3.25-3.5v3.5m3.5-3.5l-.25 3.5");
}

.nspxuibym {
  d: path("M7.75 8.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

.q73g-z-mt {
  d: path("M3 12.5h18L19.5 20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
