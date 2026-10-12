<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ey983h00w"/><circle class="v0v8ezffz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:petal" /></template>
<style>
.ey983h00w {
  d: path("m12.56 9.05l1.08-1.35q.56-.7.4-1.59l-.28-1.57q-.16-.89-.92-.41l-.08.04q-.76.48-1.52 0l-.08-.04q-.76-.48-.92.41l-.28 1.57q-.16.89.4 1.59l1.08 1.35q.56.7 1.12 0m2.66 2.74l1.61.61q.84.32 1.64-.1l1.41-.76q.79-.43.1-1l-.06-.06q-.69-.58-.47-1.45l.02-.09q.21-.87-.68-.75l-1.59.22q-.89.13-1.38.88l-.95 1.44q-.49.75.35 1.06m-1.79 3.38l-.08 1.72q-.04.9.61 1.52l1.15 1.11q.65.63.99-.21l.03-.08q.34-.83 1.23-.89l.09-.01q.9-.06.51-.87l-.7-1.45q-.39-.81-1.26-1.04l-1.66-.46q-.87-.24-.91.66m-3.77-.66L8 14.97q-.87.23-1.26 1.04l-.7 1.45q-.39.81.51.87l.09.01q.89.06 1.23.89l.03.08q.34.84.99.21l1.15-1.11q.65-.62.61-1.52l-.08-1.72q-.04-.9-.91-.66m-.53-3.78l-.95-1.44q-.49-.75-1.38-.88l-1.59-.22q-.89-.12-.68.75l.02.09q.22.87-.47 1.45l-.06.06q-.69.57.1 1l1.41.76q.8.42 1.64.1l1.61-.61q.84-.31.35-1.06M12 8.75v-1.5m3.33 3.92l1.43-.47m-2.7 4.38l.88 1.22m-5-1.22l-.88 1.22m-.39-5.13l-1.43-.47");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0v8ezffz {
  cx: 12px;
  cy: 12.25px;
  r: 1.25px;
}

</style>
