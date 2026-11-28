<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t_1d5xise"/><path class="hx0knq-np"/><path clip-rule="evenodd" class="bjulqo_nq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-tunnel-two-tone" /></template>
<style>
.bjulqo_nq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 15C11 15.552 10.552 16 10 16C9.448 16 9 15.552 9 15C9 14.448 9.448 14 10 14C10.552 14 11 14.448 11 15ZM15 15C15 15.552 14.552 16 14 16C13.448 16 13 15.552 13 15C13 14.448 13.448 14 14 14C14.552 14 15 14.448 15 15Z");
  stroke: none;
}

.hx0knq-np {
  d: path("M2 22V7C2 4.239 4.239 2 7 2H17C19.761 2 22 4.239 22 7V22M18 11V9C18 7.895 17.105 7 16 7H8C6.895 7 6 7.895 6 9V11M18 11V17C18 18.105 17.105 19 16 19M18 11H6M16 19H8M16 19L17.5 22M8 19C6.895 19 6 18.105 6 17V11M8 19L6.5 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t_1d5xise {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6H16C17.657 6 19 7.343 19 9V17C19 18.657 17.657 20 16 20H8C6.343 20 5 18.657 5 17V9C5 7.343 6.343 6 8 6H12Z");
  stroke: none;
}

</style>
