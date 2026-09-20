<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbuqwbcrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-up-alt-outline-rounded" /></template>
<style>
.jbuqwbcrl {
  fill: currentColor;
  d: path("M8.818 17.682Q7.5 16.363 7.5 14.5q0-1.748 1.138-3.005t2.862-1.472V4.921L9.754 6.667q-.14.14-.341.15q-.202.01-.367-.155q-.16-.16-.16-.354t.16-.354l2.388-2.388q.132-.131.268-.184q.137-.053.298-.053t.298.053t.268.184l2.388 2.388q.14.14.15.341t-.15.367q-.166.165-.357.165t-.357-.165l-1.74-1.74v5.101q1.725.216 2.863 1.472T16.5 14.5q0 1.864-1.318 3.182T12 19t-3.182-1.318m5.663-.701Q15.5 15.96 15.5 14.5t-1.02-2.48T12 11t-2.48 1.02T8.5 14.5t1.02 2.48T12 18t2.48-1.02M12 14.5");
}

</style>
