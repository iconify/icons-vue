<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cu9701q6c"/><path class="aaehow3va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:p-button" /></template>
<style>
.aaehow3va {
  fill: currentColor;
  d: path("M52 2H12C6.476 2 2 6.477 2 12v40c0 5.523 4.477 10 10 10h40c5.523 0 10-4.477 10-10V12c0-5.523-4.477-10-10-10M33.998 37.453h-5.571V52H21V12h12.999C41.168 12 47 17.707 47 24.727c0 7.017-5.832 12.726-13.002 12.726");
}

.cu9701q6c {
  fill: currentColor;
  d: path("M33.998 19.271h-5.571v10.91h5.571c3.072 0 5.572-2.447 5.572-5.455s-2.5-5.455-5.572-5.455");
}

</style>
