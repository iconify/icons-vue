<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="qtzvc1bme"/><path class="fvb86qb4c"/><path class="cwg44nb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-off-broken" /></template>
<style>
.cwg44nb9l {
  d: path("M12.5 7.0415C12.3374 7.0142 12.1704 7 12 7C10.3431 7 9 8.3431 9 10C9 11.3538 9.8967 12.4981 11.1285 12.8715");
}

.fvb86qb4c {
  d: path("M19.6624 7.79358C19.8822 8.53758 20.0004 9.32638 20.0004 10.1433C20.0004 14.6055 17.4471 19.8124 13.4633 21.6744C12.5347 22.1085 11.4661 22.1085 10.5375 21.6744C9.52226 21.1999 8.59986 20.5082 7.78906 19.6669");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qtzvc1bme {
  d: path("M5 15.2161C4.3525 13.5622 4 11.8013 4 10.1433C4 5.6459 7.5817 2 12 2C14.7043 2 17.0952 3.3658 18.5432 5.4568");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

</style>
