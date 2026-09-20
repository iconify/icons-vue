<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x7pc38hlb"/><path class="gjqnxybsg"/><path class="e7rn3-bmb"/><path class="sena13bvn"/><path class="c05ekebqj"/><circle class="l0r3_lbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mouse" /></template>
<style>
.c05ekebqj {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M14.37 17.683c0 1.788-1.141 3.239-2.548 3.239s-2.548-1.451-2.548-3.239s1.14-3.238 2.548-3.238c1.407-.001 2.548 1.449 2.548 3.238");
}

.e7rn3-bmb {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 23.902c0-7.973-6.554-9.752-11.381-8.787c-9.38 1.876-11.132 6.442-11.132 10.194c0 4.922 9.149 4.69 14.071 4.69S33 28.825 33 23.902");
}

.gjqnxybsg {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M12 26.717c0-2.85 3-7.035 0-7.035c-4 0-10.137 6.566-10.137 8.442S8.304 30 11.153 30s.847-.434.847-3.283");
}

.l0r3_lbwq {
  cx: 8.5px;
  cy: 24.5px;
  r: 1.5px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.sena13bvn {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M25 22.496L7.894 24.371L11.425 30H25zm-8.082-5.353c0-2.683-1.997-4.858-4.458-4.858C9.997 12.286 8 14.46 8 17.143S9.997 22 12.46 22c2.461 0 4.458-2.174 4.458-4.857");
}

.x7pc38hlb {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M30 36H17a1 1 0 1 1 0-2h13c2.542 0 4-1.367 4-3.75c0-1.537-1.643-3.25-4-3.25h-7a1 1 0 1 1 0-2h7c3.589 0 6 2.715 6 5.25c0 3.493-2.355 5.75-6 5.75");
}

</style>
