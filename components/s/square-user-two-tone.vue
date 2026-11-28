<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xtha7_b7h"/><path class="o64m7abtr"/><path clip-rule="evenodd" class="mwq6-s0lv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-user-two-tone" /></template>
<style>
.mwq6-s0lv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.121 11.1213C13.579 11.6631 12.828 12 12 12C10.343 12 9 10.6569 9 9C9 7.3432 10.343 6 12 6C13.657 6 15 7.3432 15 9C15 9.8282 14.663 10.5795 14.121 11.1213ZM6 20V19C6 16.2386 8.239 14 11 14H13C15.761 14 18 16.2386 18 19V20H6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o64m7abtr {
  d: path("M6 3H18C19.657 3 21 4.3432 21 6V18C21 19.6569 19.657 21 18 21H6C4.343 21 3 19.6569 3 18V6C3 4.3432 4.343 3 6 3Z");
}

.xtha7_b7h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H18C20.209 2 22 3.7909 22 6V18C22 20.2092 20.209 22 18 22H6C3.791 22 2 20.2092 2 18V6C2 3.7909 3.791 2 6 2H12Z");
  stroke: none;
}

</style>
