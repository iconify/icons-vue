<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="o5-exvyoi"/><path class="ba8swimwv"/><path class="penvzjvax"/><path class="hhd6xgstg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:speedometer" /></template>
<style>
.ba8swimwv {
  d: path("m29.49 21.514l-4.467 4.174l-.98 11.89h17.22l.98-11.896l-3.782-4.187");
}

.hhd6xgstg {
  d: path("m18.509 26.486l-.565 6.901H8.976l.563-6.882zM6.737 10.423l3.776 4.19M21.72 37.577l-3.776-4.19M4.5 37.577l4.476-4.19");
}

.o5-exvyoi {
  d: path("m29.082 26.506l-3.78-4.188l.979-11.895H43.5l-.98 11.889l-4.467 4.174");
}

.penvzjvax {
  d: path("m38.052 26.486l-.565 6.901H28.52l.564-6.882zM43.5 10.423l-4.476 4.19m-12.744-4.19l3.776 4.19m11.207 22.964l-3.776-4.19m-7.996-11.873l.565-6.901h8.968l-.563 6.882zm-5.447 16.063l4.475-4.19m-7.343-9.392l-2.667 2.491m-8.562-4.972L5.48 25.688l-.98 11.89h17.22l.979-11.896l-3.782-4.187zl.566-6.901h8.968l4.476-4.19H6.737l-.98 11.895l3.782 4.187");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
