<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v747hjbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-up-alt-outline-sharp" /></template>
<style>
.v747hjbug {
  fill: currentColor;
  d: path("M8.818 17.682Q7.5 16.363 7.5 14.5q0-1.748 1.138-3.005t2.862-1.472V4.921L9.4 7.016l-.708-.708L12 3l3.308 3.308l-.708.713l-2.1-2.1v5.102q1.725.216 2.863 1.472T16.5 14.5q0 1.864-1.318 3.182T12 19t-3.182-1.318m5.663-.701Q15.5 15.96 15.5 14.5t-1.02-2.48T12 11t-2.48 1.02T8.5 14.5t1.02 2.48T12 18t2.48-1.02M12 14.5");
}

</style>
