<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m87ncbvgi"/><g class="y9tr6bcfx"><path class="i5lni3jwu"/><path class="ga21qac6w"/></g><path class="n8f8vibnx"/><circle class="egy3x7kfo"/><circle class="r5cg7-elr"/><circle class="dw3qle64r"/><circle class="nwn6cgbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qudianyun" /></template>
<style>
.dw3qle64r {
  cx: 33.292px;
  cy: 20.263px;
  r: 0.75px;
  fill: currentColor;
}

.egy3x7kfo {
  cx: 31.964px;
  cy: 21.591px;
  r: 0.75px;
  fill: currentColor;
}

.ga21qac6w {
  d: path("M15.55 33.197c.277-2.923 4.486-5.216 8.45-5.216s8.173 2.293 8.45 5.216c.445 4.706-5.07 6.965-8.45 6.965s-8.895-2.259-8.45-6.965");
}

.i5lni3jwu {
  d: path("M27.16 32.3c-.541.932-1.784 1.537-3.16 1.537s-2.619-.605-3.16-1.537");
}

.m87ncbvgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.736 27.24c-.396-2.994-.036-7.057 1.87-10.554c-2.903-2.15-2.877-6.79.175-9.528c3.35-3.007 7.662-1.675 8.857 1.984C19.18 8.422 21.657 7.95 24 7.95s4.82.471 6.362 1.192c1.195-3.659 5.507-4.991 8.857-1.984c3.052 2.738 3.078 7.379.175 9.528c1.906 3.497 2.266 7.56 1.87 10.553C39.992 36.856 34.146 42.501 24 42.501S8.008 36.856 6.736 27.239");
}

.n8f8vibnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.6 15.098c-3.103 0-5.597 2.804-5.618 5.777c-.021 3.084 2.175 5.758 5.277 5.739c3.477-.022 3.794-3.14 8.741-3.14s5.264 3.118 8.741 3.14c3.102.02 5.298-2.655 5.277-5.74c-.02-2.972-2.515-5.776-5.618-5.776zm.378 3.528v3.292m1.646-1.646h-3.292");
}

.nwn6cgbzp {
  cx: 30.636px;
  cy: 20.263px;
  r: 0.75px;
  fill: currentColor;
}

.r5cg7-elr {
  cx: 31.964px;
  cy: 18.935px;
  r: 0.75px;
  fill: currentColor;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
