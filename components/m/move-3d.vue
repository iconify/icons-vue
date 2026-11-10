<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5ts43bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:move-3d" /></template>
<style>
.i5ts43bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16L12 13M12 13L16 16M12 13V10M8.4275 8.75L11.5659 3.25C11.7578 2.92 12.2422 2.92 12.4341 3.25L15.5725 8.75C15.763 9.08 15.5223 9.5 15.1384 9.5H8.8616C8.4777 9.5 8.237 9.08 8.4275 8.75ZM19.342 14.36L20.9821 20.38C21.0824 20.74 20.7449 21.08 20.3771 20.98L14.3634 19.34C13.9984 19.24 13.8771 18.78 14.1446 18.52L18.5182 14.14C18.7857 13.87 19.2424 14 19.342 14.36ZM4.658 14.36L3.0179 20.38C2.9176 20.74 3.2551 21.08 3.6229 20.98L9.6366 19.34C10.0016 19.24 10.1229 18.78 9.8554 18.52L5.4818 14.14C5.2143 13.87 4.7576 14 4.658 14.36Z");
}

</style>
