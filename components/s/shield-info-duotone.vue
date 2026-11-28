<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="efehyhbqb"/><path class="ianaz7b0e"/><path clip-rule="evenodd" class="cvyefvb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-info-duotone" /></template>
<style>
.cvyefvb3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 7C13 7.552 12.552 8 12 8C11.448 8 11 7.552 11 7C11 6.448 11.448 6 12 6C12.552 6 13 6.448 13 7Z");
  stroke: none;
}

.efehyhbqb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.889 20.715C15.855 21.525 14.62 22.26 13.175 22.791C12.417 23.07 11.583 23.07 10.825 22.791C7.936 21.73 5.885 19.851 4.597 18.185C3.297 16.503 3 14.427 3 12.571V6.383C3 5.774 3.259 5.243 3.64 4.861C4.016 4.484 4.521 4.24 5.065 4.175C7.443 3.893 9.249 2.703 10.328 1.655C11.229 0.782 12.771 0.782 13.672 1.655C14.752 2.703 16.557 3.893 18.935 4.175C19.479 4.24 19.984 4.484 20.36 4.861C20.741 5.243 21 5.774 21 6.383V12.571C21 14.427 20.703 16.503 19.403 18.185C18.757 19.02 17.923 19.905 16.889 20.715Z");
  stroke: none;
}

.ianaz7b0e {
  d: path("M12 17V11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
