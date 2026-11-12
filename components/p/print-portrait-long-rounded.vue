<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yullf8b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-long-rounded" /></template>
<style>
.yullf8b9o {
  fill: currentColor;
  d: path("M11.2 20.556q-1.12-.458-2.249-.838t-1.855-.574q-.54-.136-.856-.587q-.317-.451-.317-1.016v-1.31h-.115q-.348 0-.578-.23T5 15.423v-.308q0-.348.23-.577t.578-.23h.115V9.769h-.115q-.348 0-.578-.23T5 8.963v-.308q0-.348.23-.578t.578-.23h.115v-2.23q0-.677.457-1.147T7.539 4q.655 0 1.36.347t1.292.603q.467.206 1.006.432q.54.226 1.174.512q.454.198.724.602t.27.883v11.775q0 .856-.703 1.299q-.704.443-1.462.103M14.385 19V7.379q0-.977-.605-1.625t-1.764-1.077L10.474 4h5.91q.67 0 1.143.472q.472.472.472 1.144v11.769q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
