<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5w_hi63t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:surround-sound-sharp" /></template>
<style>
.a5w_hi63t {
  fill: currentColor;
  d: path("M14.125 14.125Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875m2.825 2.825q1-1 1.525-2.275T19 12t-.525-2.675T16.95 7.05l-1.4 1.4q.725.725 1.087 1.637T17 12t-.363 1.913t-1.087 1.637zm-9.9 0l1.4-1.4q-.725-.725-1.088-1.638T7 12t.363-1.912T8.45 8.45l-1.4-1.4q-1 1-1.525 2.275T5 12t.525 2.675T7.05 16.95M2 20V4h20v16z");
}

</style>
