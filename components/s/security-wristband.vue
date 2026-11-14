<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmrk-8u8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:security-wristband" /></template>
<style>
.qmrk-8u8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.31 17.226q-4.373-1.143-4.558-3.415l-.002-.061v-4q0-1.973 3.273-3.179Q7.931 5.5 12 5.5t6.977 1.071Q22.25 7.777 22.25 9.75v4l-.002.061q-.185 2.272-4.558 3.415q-.069.018-.139.022q-.837 1.002-2.676 1.002h-5.75q-1.839 0-2.676-1.002q-.07-.004-.139-.022M20.749 9.72q-.036-.91-2.291-1.741Q15.801 7 12 7t-6.458.979Q3.287 8.81 3.251 9.72q.125 1.076 2.825 1.883Q6.799 10 9.125 10h5.75q2.326 0 3.049 1.603q2.7-.807 2.825-1.883M3.25 11.986v1.729q.112 1.019 2.533 1.797q-.033-.302-.033-.637v-1.5q0-.155.007-.303q-1.555-.462-2.507-1.086m17.5 1.729v-1.729q-.952.624-2.507 1.086q.007.148.007.303v1.5q0 .335-.033.637q2.421-.778 2.533-1.797");
}

</style>
