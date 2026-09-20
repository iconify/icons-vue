<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bjpyf19-j"/><path class="rivnzhbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:speech-balloon" /></template>
<style>
.bjpyf19-j {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M20.79 126.61V96.9h-6.38C5.98 96.9.95 91.86.95 83.43V14.01C.95 6.94 6.86 1.4 14.41 1.4h99.18c7.67 0 13.46 5.42 13.46 12.61v69.43c0 8.18-5.28 13.47-13.46 13.47H51z");
}

.rivnzhbxk {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.41 8.48c-3.17 0-6.37 1.9-6.37 5.52v69.43c0 4.53 1.85 6.37 6.37 6.37h13.47v19.88L48.1 89.81h65.49c4.29 0 6.37-2.09 6.37-6.37V14.01c0-3.62-3.2-5.52-6.37-5.52H14.41z");
}

</style>
