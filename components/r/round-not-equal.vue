<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlxuxlbuw"/><path class="eae5qyb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-not-equal" /></template>
<style>
.eae5qyb6x {
  fill: currentColor;
  d: path("M14.999 5c.507.219.742.806.525 1.314l-5.212 12.162A1 1 0 0 1 9 19a1 1 0 0 1-.525-1.314l5.212-12.162A1 1 0 0 1 15 5z");
}

.wlxuxlbuw {
  fill: currentColor;
  d: path("M18 9.998H6a1 1 0 1 1 0-2h12a1 1 0 0 1 0 2m0 6H6a1 1 0 0 1 0-2h12a1 1 0 0 1 0 2");
}

</style>
