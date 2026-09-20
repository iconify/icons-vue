<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGidErOASs" class="rgxscmb6m"/></defs><clipPath id="SVGw4krnjIV"><use href="#SVGidErOASs"/></clipPath><path clip-path="url(#SVGw4krnjIV)" class="ad_fkebqo"/><g clip-path="url(#SVGw4krnjIV)"><path class="i-hdd0b7n"/><path class="bhxyl7egw"/><path class="e--8wjcwa"/></g><path class="yqyvhtzrz"/><defs><path id="SVGeyJnXchD" class="j7rnhsb6g"/></defs><use href="#SVGeyJnXchD" class="j71m3fb1u"/><path class="wtvuo2b0g"/><path class="uxnmdkbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:mountain-railway" /></template>
<style>
.ad_fkebqo {
  fill: var(--svg-color--757f3f, #757f3f);
  d: path("M64 19.44c-50 0-73.49 65.07-73.49 65.07l2.67 56.54h141.66l2.67-56.54c-.02 0-23.5-65.07-73.51-65.07");
}

.bhxyl7egw {
  fill: var(--svg-color--855c52, #855c52);
  d: path("M122.42 127.87H5.57l22.82-13.71H99.6z");
}

.e--8wjcwa {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M49.46 127.98h-7.72l8.7-13.87h4.7zm29.07 0h7.72l-8.69-13.87h-4.7z");
}

.i-hdd0b7n {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 46.33c-19.66 0-35.61 15.94-35.61 35.61v32.22H99.6V81.94c0-19.67-15.94-35.61-35.6-35.61");
}

.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.j7rnhsb6g {
  d: path("M86.79 97.74c0 5.71-4.63 10.33-10.34 10.33h-25c-5.7 0-10.34-4.62-10.34-10.33V69.26c0-5.71 4.64-10.33 10.34-10.33h25.01c5.72 0 10.34 4.62 10.34 10.33v28.48z");
}

.rgxscmb6m {
  d: path("M127.99 115.89c0 6.66-5.44 12.1-12.09 12.1H12.1c-6.65 0-12.1-5.44-12.1-12.1V12.1C0 5.44 5.44 0 12.1 0h103.8c6.65 0 12.09 5.44 12.09 12.1z");
}

.uxnmdkbak {
  fill: var(--svg-color--fff, #fff);
  d: path("M53.27 97.75c0 2.07-1.68 3.75-3.75 3.75c-2.08 0-3.75-1.68-3.75-3.75c0-2.08 1.68-3.75 3.75-3.75s3.75 1.67 3.75 3.75m21.36 0c0 2.07 1.67 3.75 3.75 3.75c2.07 0 3.75-1.68 3.75-3.75c0-2.08-1.67-3.75-3.75-3.75c-2.07 0-3.75 1.67-3.75 3.75");
}

.wtvuo2b0g {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M82.23 74.99c0 3.08-2.49 5.58-5.57 5.58H51.24c-3.08 0-5.58-2.5-5.58-5.58v-7.05c0-3.08 2.51-5.58 5.58-5.58h25.42c3.08 0 5.57 2.5 5.57 5.58z");
}

.yqyvhtzrz {
  fill: var(--svg-color--fff, #fff);
  d: path("M54.83 113.11c0 1.24-1 2.25-2.25 2.25c-1.24 0-2.25-1.01-2.25-2.25v-8.66c0-1.24 1-2.25 2.25-2.25s2.25 1.01 2.25 2.25zm18.23 0c0 1.24 1 2.25 2.25 2.25s2.25-1.01 2.25-2.25v-8.66c0-1.24-1.01-2.25-2.25-2.25c-1.25 0-2.25 1.01-2.25 2.25z");
}

</style>
