<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf5tgeqen"/><path class="g7lf42b8j"/><path class="kjee7xvdg"/><path class="jqlk-kbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-4-bold" /></template>
<style>
.g7lf42b8j {
  fill: currentColor;
  d: path("M21 14C21 14.839 20.9983 15.5847 20.9854 16.25L3.01562 16.25C3.00272 15.5847 3 14.8391 3 14L3 12.75L21 12.75L21 14Z");
}

.jqlk-kbvz {
  fill: currentColor;
  d: path("M3.08105 6.25C3.19632 4.81075 3.4777 3.86605 4.17187 3.17187C5.34345 2.0003 7.22876 2 11 2L13 2C16.7712 2 18.6566 2.0003 19.8281 3.17187C20.5223 3.86606 20.8047 4.81071 20.9199 6.25L3.08105 6.25Z");
}

.kjee7xvdg {
  fill: currentColor;
  d: path("M20.9199 17.75C20.8047 19.1893 20.5223 20.1339 19.8281 20.8281C18.6566 21.9997 16.7712 22 13 22L11 22C7.22876 22 5.34345 21.9997 4.17187 20.8281C3.4777 20.1339 3.19632 19.1892 3.08105 17.75L20.9199 17.75Z");
}

.rf5tgeqen {
  fill: currentColor;
  d: path("M3 11.25L3 10C3 9.16094 3.00272 8.41528 3.01562 7.75L20.9854 7.75C20.9983 8.41527 21 9.16095 21 10L21 11.25L3 11.25Z");
}

</style>
