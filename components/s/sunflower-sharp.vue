<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jab24-bim"/><circle class="srqzxr9-m"/><path class="y1tx78q_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunflower-sharp" /></template>
<style>
.jab24-bim {
  d: path("m12.25 3.3l.53 1.17l.24.55l.46-.39l.99-.83l.46-.38l-.02.6l-.03 1.28l-.01.6l.58-.14l1.25-.32l.58-.15l-.28.54l-.58 1.14l-.28.53l.59.12l1.26.26l.59.12l-.48.36l-1.02.78l-.48.36l.48.36l1.02.78l.48.36l-.59.12l-1.26.26l-.59.12l.28.53l.58 1.14l.28.54l-.58-.15l-1.25-.32l-.58-.14l.01.6l.03 1.28l.02.6l-.46-.38l-.99-.83l-.46-.39l-.24.55l-.53 1.17l-.25.55l-.25-.55l-.53-1.17l-.24-.55l-.46.39l-.99.83l-.46.38l.02-.6l.03-1.28l.01-.6l-.58.14l-1.25.32l-.58.15l.28-.54l.58-1.14l.28-.53l-.59-.12l-1.26-.26l-.59-.12l.48-.36l1.02-.78l.48-.36l-.48-.36l-1.02-.78L5.42 8l.59-.12l1.26-.26l.59-.12l-.28-.53L7 5.83l-.28-.54l.58.15l1.25.32l.58.14l-.01-.6l-.03-1.28l-.02-.6l.46.38l.99.83l.46.39l.24-.55l.53-1.17l.25-.55z");
}

.srqzxr9-m {
  cx: 12px;
  cy: 9.5px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1tx78q_k {
  d: path("M12 16.25v5M12 20c.5-1.75 2.25-2.75 4.5-2.75C16 19 14.25 20 12 20Z");
}

</style>
