<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4mohp1lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:usb" /></template>
<style>
.w4mohp1lo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.352 5.506l2.072-2.486q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028t.147.001t.144.03t.136.057q.064.036.121.083q.053.043.096.096l2.5 3q.022.026.041.054q.53-.324 1.383-.324q2.25 0 2.25 2.25q0 1.837-1.5 2.174V11.5q0 .1-.026.197q-.027.097-.078.183q-.05.087-.122.157t-.16.119l-4.114 2.285v1.869q2 .345 2 2.69q0 2.75-2.75 2.75T9.25 19q0-2.345 2-2.69v-3.869l-4.114-2.285q-.088-.049-.16-.119t-.122-.157q-.051-.086-.078-.183Q6.75 9.6 6.75 9.5v-.326Q5.25 8.837 5.25 7q0-2.25 2.25-2.25q1.304 0 1.852.756m.393 1.703q-.078 1.563-1.353 1.929l2.858 1.587V5.572L10.076 6.98q-.134.161-.331.229m3.005 5.516l3-1.666v-.885q-1.5-.337-1.5-2.174q0-.425.08-.769q-.119-.028-.223-.092q-.105-.065-.183-.159L12.75 5.572z");
}

</style>
