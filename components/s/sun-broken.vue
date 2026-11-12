<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lq7a-_8su"/><path class="pq5xj2bli"/><path class="qi4ad9bta"/><path class="i0kw3he6n"/><path class="de5cici1x"/><path class="f1qgw1bwi"/><path class="elckf4blp"/><path class="ftpy_bcfw"/><path class="mgzczt2-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-broken" /></template>
<style>
.de5cici1x {
  d: path("M19.0703 4.9292L18.6775 5.32204");
}

.elckf4blp {
  d: path("M19.0703 19.0708L18.6775 18.678");
}

.f1qgw1bwi {
  d: path("M5.32227 18.6782L4.92943 19.0711");
}

.ftpy_bcfw {
  d: path("M5.32227 5.32178L4.92943 4.92894");
}

.i0kw3he6n {
  d: path("M3 12L2 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lq7a-_8su {
  d: path("M12 2V3");
}

.mgzczt2-e {
  d: path("M6.34141 10C6.12031 10.6256 6 11.2987 6 12C6 15.3137 8.68629 18 12 18C15.3137 18 18 15.3137 18 12C18 8.68629 15.3137 6 12 6C11.2987 6 10.6256 6.12031 10 6.34141");
}

.pq5xj2bli {
  d: path("M12 21V22");
}

.qi4ad9bta {
  d: path("M22 12L21 12");
}

</style>
