<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b4ojaf29j"/><path class="hh30wfbqs"/><path class="emchkfb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sprint-duotone" /></template>
<style>
.b4ojaf29j {
  stroke-opacity: 0.4;
  d: path("M3 21L6.3391 18.6149C6.4425 18.5411 6.5139 18.4307 6.5388 18.3061L7 16");
}

.emchkfb3l {
  fill: currentColor;
  d: path("M21.1213 2.8787C21.6631 3.4205 22 4.1718 22 5C22 6.6569 20.6569 8 19 8C17.3431 8 16 6.6569 16 5C16 3.3431 17.3431 2 19 2C19.8282 2 20.5795 2.3369 21.1213 2.8787Z");
  stroke: none;
}

.hh30wfbqs {
  d: path("M19 12.5L16.5122 13.3293C16.2359 13.4214 15.9397 13.2587 15.869 12.9762L15.0795 9.818C15.0312 9.6249 14.873 9.4788 14.6766 9.4461L9.2538 8.5423C9.0945 8.5158 8.9322 8.5678 8.8181 8.6819L6 11.5M11 20L13.6734 16.4355C13.8491 16.2012 13.7867 15.8667 13.5384 15.7115L10.5664 13.854C10.2834 13.6771 10.2498 13.278 10.4992 13.0563L14.5 9.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
