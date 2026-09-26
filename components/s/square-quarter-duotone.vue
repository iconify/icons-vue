<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jz28tybvv"/><path class="rtoum7b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-quarter-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jz28tybvv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.79086 3.79086 2 6 2H18C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6Z");
}

.rtoum7b9n {
  d: path("M12 6L15.5 6C16.8807 6 18 7.1193 18 8.5L18 12C18 12.5523 17.5523 13 17 13L12 13C11.4477 13 11 12.5523 11 12L11 7C11 6.4477 11.4477 6 12 6Z");
}

</style>
