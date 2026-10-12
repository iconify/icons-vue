<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dldnhmbjp"/><path class="o_u414buc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-picker" /></template>
<style>
.dldnhmbjp {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_u414buc {
  d: path("M12 7.25V12l-3 2m5.95.51l5.35 1.98q.7.26-.02.48l-1.81.56q-.72.22-.94.94l-.56 1.81q-.22.72-.48.02l-1.98-5.35q-.26-.7.44-.44");
}

</style>
