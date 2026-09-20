<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGM1Hbzebt)" class="oacyd9b7s"/><defs><linearGradient id="SVGM1Hbzebt" x1="3.312" x2="22.295" y1="18.984" y2="15.144" gradientUnits="userSpaceOnUse"><stop class="dlupnn6qn"/><stop offset=".54" class="sll0kmo4p"/><stop offset=".8" class="ct0o6k2bn"/><stop offset="1" class="fk3a3gb7j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pts" /></template>
<style>
.ct0o6k2bn {
  stop-color: var(--svg-color--9246e2, #9246e2);
}

.dlupnn6qn {
  stop-color: var(--svg-color--fd8c30, #fd8c30);
}

.fk3a3gb7j {
  stop-color: var(--svg-color--6966ff, #6966ff);
}

.ft5dv1b6b {
  fill: none;
}

.oacyd9b7s {
  d: path("M11.1 3.739A6.84 6.84 0 0 0 7.32 6.24c-.409.612-.66 1.398-2.16 6.731a112 112 0 0 1-1.95 6.498c-.139.252-.234.57-.204.702c.042.222.168.24 1.5.222c1.847-.018 2.25-.096 2.67-.522c.545-.558.743-1.08 1.547-4.11c1.116-4.218 1.818-6.42 2.202-6.93c.714-.971 2.076-1.031 3.744-1.031c1.404 0 1.44-.162.504 3.12c-.414 1.44-1.734 2.364-3.612 2.52c-.48.035-.948.12-1.032.191c-.21.174-.198 1.297.018 1.728c.606 1.182 2.1 1.41 3.336 1.44c2.112.06 3.678-.978 4.746-3.24c.732-1.542.948-2.322 1.38-4.913c.216-1.284.564-2.88.78-3.54c.096-.288.162-.6.204-.87c.054-.342-.222-.636-.57-.636h-4.158s-4.59-.006-5.172.138z");
}

.sll0kmo4p {
  stop-color: var(--svg-color--c720b6, #c720b6);
}

</style>
