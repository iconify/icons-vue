<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g297u1bre"/><path class="zsfw75g9a"/><path class="ag47ypk4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-play-circle" /></template>
<style>
.ag47ypk4w {
  fill: currentColor;
  d: path("m9.5 16.5l7-4.5l-7-4.5z");
}

.g297u1bre {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8M9.5 16.5v-9l7 4.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zsfw75g9a {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8");
}

</style>
