<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ew7sas6dz"/><path class="y0wr_bbqj"/><circle class="r974plbft"/><circle class="mlu15ve1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:south-park-phone-destroyer-alt" /></template>
<style>
.ew7sas6dz {
  cx: 24px;
  cy: 26.084px;
  r: 18.414px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mlu15ve1a {
  cx: 20.957px;
  cy: 27.613px;
  r: 0.75px;
  fill: currentColor;
}

.r974plbft {
  cx: 28.209px;
  cy: 26.958px;
  r: 0.75px;
  fill: currentColor;
}

.y0wr_bbqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.432 39.168q2.65-1.16 5.86-.303m-4.77-9.4c-.944 2.81-3.57 4.463-5.863 3.691s-3.386-3.675-2.44-6.486s3.57-4.463 5.864-3.692c2.293.773 3.386 3.675 2.44 6.486m2.882-6.795c2.038-1.303 4.985-.334 6.583 2.164s1.24 5.58-.798 6.884c-2.039 1.303-4.984.334-6.583-2.163s-1.24-5.581.797-6.885zm-20.645.859c11.739-4.712 23.325-5.82 35.656-3.437M20.392 3.5l.541 4.408l1.379-4.303l-1.379 4.303l3.088-3.544l-3.088 3.543l4.329-2.242l-4.329 2.242l4.909-.602l-4.909.602l4.743 1.13l-4.743-1.13l3.854 2.691l-3.854-2.691l2.379 3.842l-2.379-3.842l.541 4.408l-.541-4.408l-1.377 4.304l1.377-4.304l-3.086 3.543l3.086-3.543l-4.326 2.243l4.326-2.243l-4.906.604l4.906-.604l-4.74-1.129l4.74 1.129l-3.852-2.69l3.852 2.69l-2.377-3.841l2.377 3.841z");
}

</style>
