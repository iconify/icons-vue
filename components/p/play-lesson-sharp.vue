<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyat-ibwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-lesson-sharp" /></template>
<style>
.cyat-ibwb {
  fill: currentColor;
  d: path("M4 21V3h14v8.735q-.22-.031-.5-.031t-.5.03q-2.379.189-3.94 1.91q-1.56 1.722-1.56 4.048q0 .87.26 1.723q.261.852.72 1.585zm10.665-.472Q13.5 19.364 13.5 17.692q0-1.67 1.165-2.835q1.164-1.165 2.835-1.165t2.836 1.165t1.164 2.835t-1.164 2.836t-2.836 1.164t-2.835-1.164m1.97-.951l2.73-1.923l-2.73-1.923zM7.5 10.192L9.5 9l2 1.192V4h-4z");
}

</style>
