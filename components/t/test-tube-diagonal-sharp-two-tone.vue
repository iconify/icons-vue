<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pel4bdbze"/><path class="j9yjuybdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-diagonal-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j9yjuybdg {
  d: path("M14.1339 2.5456L19.162 5.8195L9.514 20.6369C8.9604 21.4872 8.0146 22 7 22C5.3431 22 4 20.6569 4 19C4 18.4188 4.1688 17.8501 4.486 17.3631L14.1339 2.5456ZM13.0471 1.838L20.4544 6.661M7.3268 13L14.4866 13");
}

.pel4bdbze {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.6796 1.7076L19.7076 4.9815C19.991 5.1661 20.162 5.4814 20.162 5.8195C20.162 6.0133 20.1057 6.2028 20 6.3652L10.3521 21.1826C9.6139 22.3162 8.3528 23 7 23C4.7909 23 3 21.2091 3 19C3 18.2251 3.2251 17.4668 3.6479 16.8174L13.2959 2C13.4804 1.7166 13.7957 1.5456 14.1339 1.5456C14.3276 1.5456 14.5172 1.6019 14.6796 1.7076Z");
  stroke: none;
}

</style>
