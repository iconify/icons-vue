<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jhqtufb1f"/><path class="n7bew3b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pentagon-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jhqtufb1f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.1428 6.0203L21.6417 9.8061C21.8675 9.9961 21.9978 10.2761 21.9978 10.5712C21.9978 10.6727 21.9823 10.7737 21.9519 10.8705L18.68 21.2996C18.5492 21.7166 18.1629 22.0003 17.7259 22.0003L6.2741 22.0003C5.8371 22.0003 5.4508 21.7166 5.32 21.2996L2.0481 10.8705C2.0177 10.7737 2.0022 10.6727 2.0022 10.5712C2.0022 10.2761 2.1325 9.9961 2.3583 9.8061L11.3561 2.2346C11.5364 2.0829 11.7644 1.9997 12 1.9997C12.2356 1.9997 12.4636 2.0829 12.6439 2.2346Z");
  stroke: none;
}

.n7bew3b7x {
  d: path("M3.0022 10.5712L6.2741 21.0003L17.7259 21.0003L20.9978 10.5712L12 2.9997Z");
}

</style>
