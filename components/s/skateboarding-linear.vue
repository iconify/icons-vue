<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="um3c8ib4d"/><circle class="pyd8uurcz"/><path class="sku8d52nq"/><path class="e_3yci41k"/><path class="noetulbxy"/><path class="kg7-urb4q"/><path class="b96xznzsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboarding-linear" /></template>
<style>
.b96xznzsu {
  stroke-linejoin: round;
  d: path("M17 21H17.0001");
}

.e_3yci41k {
  d: path("M7 15.5H7.37868C8.73694 15.5 10.0396 14.9604 11 14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kg7-urb4q {
  stroke-linejoin: round;
  d: path("M7 21H7.0001");
}

.noetulbxy {
  d: path("M16.5 10C17.8131 10.3283 19.1869 10.3283 20.5 10");
}

.pyd8uurcz {
  cx: 19px;
  cy: 4px;
  r: 2px;
}

.sku8d52nq {
  d: path("M15 16.4999V15.2491C15 15.1652 15 15.1233 14.999 15.0838C14.9732 14.1057 14.4721 13.2016 13.6563 12.6614C13.6234 12.6396 13.5842 12.6151 13.5057 12.566L13.5055 12.5659C13.4088 12.5054 13.3604 12.4752 13.3291 12.454C12.241 11.7153 12.1498 10.1456 13.145 9.28581C13.1735 9.26111 13.2125 9.22996 13.2903 9.1677L13.7358 8.81128C14.7607 7.99138 14.5413 6.37478 13.3349 5.85776C12.8119 5.63361 12.2123 5.67979 11.7297 5.98137L8.5 7.99995");
}

.um3c8ib4d {
  stroke-linejoin: round;
  d: path("M3 17L4.20414 18.3379C4.58342 18.7594 5.12375 19 5.69073 19H18.3093C18.8762 19 19.4166 18.7594 19.7959 18.3379L21 17");
}

</style>
