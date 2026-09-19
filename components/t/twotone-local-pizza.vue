<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw8nz1m0l"/><path class="zfr7p4bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-pizza" /></template>
<style>
.sw8nz1m0l {
  fill: currentColor;
  d: path("M5.51 6.36L12 17.92l6.49-11.55C16.68 4.85 14.38 4 12 4s-4.68.85-6.49 2.36M9 8.5c-.83 0-1.5-.67-1.5-1.5S8.17 5.5 9 5.5s1.5.67 1.5 1.5S9.82 8.5 9 8.5m4.5 4.5c0 .83-.68 1.5-1.5 1.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zfr7p4bvx {
  fill: currentColor;
  d: path("M12 2C8.43 2 5.23 3.54 3.01 6L12 22l8.99-16C18.78 3.55 15.57 2 12 2m0 15.92L5.51 6.36C7.32 4.85 9.62 4 12 4s4.68.85 6.49 2.36zM9 5.5c-.83 0-1.5.67-1.5 1.5S8.17 8.5 9 8.5s1.5-.67 1.5-1.5S9.82 5.5 9 5.5m1.5 7.5c0 .83.67 1.5 1.5 1.5c.82 0 1.5-.67 1.5-1.5s-.68-1.5-1.5-1.5s-1.5.67-1.5 1.5");
}

</style>
