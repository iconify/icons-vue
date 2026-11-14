<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew_qi0iia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ounce-weight" /></template>
<style>
.ew_qi0iia {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.913 7.05l-2.48 8.5q-.35 1.2.4 2.2t2 1h14.334q1.25 0 2-1t.4-2.2l-2.48-8.5q-.525-1.799-2.399-1.8H7.313q-1.875 0-2.4 1.8m1.533 5.739l1-3Q7.959 8.25 9.581 8.25h4.838q1.622 0 2.135 1.539l1 3q.363 1.093-.31 2.027t-1.825.934H8.581q-1.152 0-1.825-.934t-.31-2.027");
}

</style>
