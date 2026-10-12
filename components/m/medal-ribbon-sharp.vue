<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zpxmtg25a"/><circle class="ptvu1u_4n"/><path class="z15bq6gan"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medal-ribbon-sharp" /></template>
<style>
.ptvu1u_4n {
  cx: 12px;
  cy: 8px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z15bq6gan {
  d: path("M8 15.5h2.75l-.06.5l-.63 4.75l-.06.5l-.32-.38l-.61-.74l-.32-.38l-.38.33l-.99.84l-.38.33l.04-.5l.42-4.75l.04-.5zm5.75 0h2.75l.04.5l.42 4.75l.04.5l-.38-.33l-.99-.84l-.38-.33l-.32.38l-.61.74l-.32.38l-.06-.5l-.63-4.75l-.06-.5z");
}

.zpxmtg25a {
  d: path("M12.56 3.27h0l.57.53l.75-.17l.75-.18l.22.74l.23.73l.73.23l.74.23l-.18.74l-.17.75l.53.57l.52.56l-.52.56l-.53.57l.17.75l.18.75l-.74.22l-.73.23l-.23.73l-.22.74l-.75-.18l-.75-.17l-.57.53l-.56.52l-.56-.52l-.57-.53l-.75.17l-.74.18l-.23-.74l-.23-.73l-.73-.23l-.74-.22l.18-.75l.17-.75l-.53-.57L6.75 8l.52-.56l.53-.57l-.17-.75l-.18-.74l.74-.23l.73-.23l.23-.73l.22-.74l.75.18l.75.17l.57-.53l.56-.52z");
}

</style>
