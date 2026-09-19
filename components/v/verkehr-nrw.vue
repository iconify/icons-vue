<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ljoepud4l"/><circle class="fem_4ibuc"/><path class="rxzw1y6zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:verkehr-nrw" /></template>
<style>
.fem_4ibuc {
  cx: 21.633px;
  cy: 35.782px;
  r: 0.753px;
  fill: currentColor;
}

.ljoepud4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.294 35.992v-5.606h1.83c1.055 0 1.9.841 1.9 1.892s-.845 1.892-1.9 1.892h-1.83m1.963-.004l1.766 1.826m-20.178-7.96h2.817m-2.817-5.564h2.817m-2.817 2.782h1.831m-1.831-2.782v5.564m4.362.001v-5.565h1.831c1.057 0 1.902.835 1.902 1.878s-.845 1.878-1.902 1.878h-1.831m1.965-.006l1.768 1.814m1.545-5.564v5.564m3.029.001l-2.325-2.783l2.325-2.782m-2.325 2.782h-.704m8.935-2.782v5.564m3.734-5.564v5.564M31.42 25.25h3.734M11.3 22.468l-1.83 5.565l-1.902-5.565m19.49 5.564h2.818m-2.818-5.564h2.818m-2.818 2.782h1.832m-1.832-2.782v5.564m9.64.001v-5.565h1.832c1.056 0 1.902.835 1.902 1.878s-.846 1.878-1.902 1.878h-1.832m1.966-.005l1.768 1.813m-16.782 7.96v-5.606q1.863 2.804 3.729 5.606v-5.606m13.054.001l-1.407 5.605l-1.407-5.605l-1.407 5.605l-1.408-5.605");
}

.rxzw1y6zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.5v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4");
}

</style>
