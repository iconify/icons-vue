<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="fa0qmtaqu"/><path class="q8vsinb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:yin-yang" /></template>
<style>
.fa0qmtaqu {
  cx: 42.264px;
  cy: 42.263px;
  r: 5.443px;
  fill: currentColor;
}

.q8vsinb2u {
  fill: currentColor;
  d: path("M32 2C15.458 2 2 15.458 2 32s13.458 30 30 30s30-13.458 30-30S48.542 2 32 2m-6.416 23.584a5.444 5.444 0 1 1-7.699-7.7a5.444 5.444 0 0 1 7.699 7.7m20.501 30.675c-4.859 1.321-10.27.086-14.086-3.729c-5.668-5.668-5.668-14.86 0-20.529s5.669-14.86 0-20.528c-3.815-3.816-9.225-5.052-14.084-3.73A27.9 27.9 0 0 1 32 3.936c15.476 0 28.064 12.589 28.064 28.064c0 10.344-5.628 19.391-13.979 24.259");
}

</style>
