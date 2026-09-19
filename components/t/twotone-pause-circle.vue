<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dijh1ybau"/><path class="gr2egokbq"/><path class="zsfw75g9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-pause-circle" /></template>
<style>
.dijh1ybau {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8m-1 12H9V8h2zm4 0h-2V8h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.gr2egokbq {
  fill: currentColor;
  d: path("M13 8h2v8h-2zM9 8h2v8H9z");
}

.zsfw75g9a {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8");
}

</style>
