<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p_a9u9axh"/><path class="uv7pidarg"/><path class="kk0xpebyx"/><path class="lq7a-_8su"/><path class="qi4ad9bta"/><path class="i0kw3he6n"/><path class="de5cici1x"/><path class="ftpy_bcfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-sun-linear" /></template>
<style>
.de5cici1x {
  d: path("M19.0703 4.9292L18.6775 5.32204");
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

.kk0xpebyx {
  d: path("M17.9161 11C17.44 8.16229 14.9721 6 11.9991 6C9.02608 6 6.55811 8.16229 6.08203 11");
}

.lq7a-_8su {
  d: path("M12 2V3");
}

.p_a9u9axh {
  stroke-linejoin: round;
  d: path("M22 16.7724C20.4123 16.3983 19.5955 15.4792 18.9199 14.457C18.4965 13.8165 17.5655 13.8554 17.1055 14.4702C16.0541 15.8758 14.4844 17 12 17C9.49345 17 7.91806 15.5696 6.86651 14.2236C6.42721 13.6612 5.58617 13.6687 5.20168 14.2699C4.50078 15.3656 3.68402 16.3756 2 16.7724");
}

.qi4ad9bta {
  d: path("M22 12L21 12");
}

.uv7pidarg {
  stroke-linejoin: round;
  d: path("M22 21.7724C20.4123 21.3983 19.5955 20.4792 18.9199 19.457C18.4965 18.8165 17.5655 18.8554 17.1055 19.4702C16.0541 20.8758 14.4844 22 12 22C9.49345 22 7.91806 20.5696 6.86651 19.2236C6.42721 18.6612 5.58617 18.6687 5.20168 19.2699C4.50078 20.3656 3.68402 21.3756 2 21.7724");
}

</style>
