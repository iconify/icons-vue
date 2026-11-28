<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g0jhc5brj"/><path class="a5h6c4bfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port-off-two-tone" /></template>
<style>
.a5h6c4bfu {
  d: path("M17.9639 17.9639C17.8118 17.9877 17.6564 18 17.4987 18L6.5013 18C5.1247 18 3.9248 17.0631 3.5909 15.7276L2.0909 9.7276C1.6175 7.8342 3.0496 6 5.0013 6L6 6M2 2L22 22");
}

.g0jhc5brj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.7872 18.7872C18.3806 18.9256 17.9467 19 17.4987 19L6.5013 19C4.6658 19 3.066 17.7508 2.6208 15.9702L1.1208 9.9701C0.4897 7.446 2.3984 5.0008 5 5ZM19.8971 15.6544L10.9498 6.7071C10.7688 6.5262 10.6569 6.2762 10.6569 6C10.6569 5.4477 11.1046 5 11.6569 5L12 5L18.9987 5C21.601 5 23.5104 7.4456 22.8792 9.9702L21.5681 15.2146C21.4511 15.6371 21.0639 15.9473 20.6042 15.9473C20.3281 15.9473 20.0781 15.8354 19.8971 15.6544Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
