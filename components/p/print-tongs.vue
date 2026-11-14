<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn_wv3b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:print-tongs" /></template>
<style>
.tn_wv3b-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.419 17.251L9.274 2.313q.015-.06.04-.117t.06-.108q.034-.052.076-.098q.042-.045.091-.083t.103-.067q.055-.03.113-.05t.12-.03t.123-.01h4q.062 0 .123.01t.12.03t.113.05q.054.029.103.067t.091.083t.076.098q.035.051.06.108t.04.117l3.855 14.938q.983.028 1.687.731q.732.732.732 1.768t-.732 1.768t-1.768.732h-1q-1.036 0-1.768-.732T15 19.75q0-2.257 2.038-2.476L13.419 3.25h-2.838L6.962 17.274Q9 17.493 9 19.75q0 1.036-.732 1.768T6.5 22.25h-1q-1.036 0-1.768-.732T3 19.75q0-2.459 2.419-2.499");
}

</style>
