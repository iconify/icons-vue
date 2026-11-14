<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oecxkfftf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smart-lock-keypad" /></template>
<style>
.oecxkfftf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 1.75h5.75q2.123 0 3.624 1.501t1.501 3.624v6.17Q18.398 13 18 13q-1.259 0-2.066.453q.066-.319.066-.703q0-2.25-2.25-2.25t-2.25 2.25T13.75 15q.58 0 1.011-.15q-.189.504-.241 1.145Q13 16.863 13 19.25v.5q0 .812.3 1.5H7.875q-2.123 0-3.624-1.501T2.75 16.125v-9.25q0-2.123 1.501-3.624T7.875 1.75m2.125 5Q10 4.5 7.75 4.5T5.5 6.75T7.75 9T10 6.75m3.75-2.25q-2.25 0-2.25 2.25T13.75 9T16 6.75T13.75 4.5M10 12.75q0-2.25-2.25-2.25T5.5 12.75T7.75 15T10 12.75m11.018 4.732q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 3.25v-.5q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707");
}

</style>
