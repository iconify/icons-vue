<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hbewjo17w"/><path class="pxmxyubpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:public-health" /></template>
<style>
.hbewjo17w {
  d: path("M2.935 14.843q.159.507.374.993q.214.486.482.945q.267.459.584.885t.679.815t.766.734t.842.644q.44.298.91.546q.47.247.964.441m.993.327q1.214.327 2.471.327q.378 0 .754-.03q.377-.03.75-.09t.74-.149t.726-.207t.708-.265q.348-.146.684-.32q.335-.173.656-.373q.321-.199.625-.424t.589-.472t.55-.518q.265-.269.507-.559t.461-.598t.412-.633t.36-.664t.306-.69t.251-.712m.002-5.586q-.111-.362-.25-.713q-.14-.352-.307-.691t-.36-.664t-.412-.633q-.218-.309-.461-.599q-.242-.29-.507-.56q-.264-.27-.549-.518t-.59-.473q-.304-.224-.625-.424q-.32-.2-.656-.373q-.336-.174-.685-.321q-.348-.146-.707-.264t-.727-.208q-.367-.089-.74-.149t-.75-.09T12 2.5q-.887 0-1.76.164q-.872.165-1.698.488m-1.6.806q-.354.223-.688.476q-.333.254-.643.535t-.594.59q-.284.308-.54.639q-.255.332-.481.685q-.226.352-.419.724q-.194.371-.354.758t-.286.786");
}

.pxmxyubpv {
  d: path("M12 2.5c-1.013 1.013-1.733 2.74-2.16 4.766m.718 11.895c.386.959.867 1.764 1.442 2.339m0-19c1.327 1.327 2.151 3.875 2.471 6.718m.001 5.56c-.321 2.845-1.145 5.395-2.472 6.722M2.5 12H6l1.5-3l2 6l1.5-3h10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
