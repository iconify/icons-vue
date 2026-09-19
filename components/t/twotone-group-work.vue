<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6wc2vl1z"/><path class="zsfw75g9a"/><circle class="kgneaxreo"/><circle class="x621cbc6b"/><circle class="czwmjhe3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-group-work" /></template>
<style>
.czwmjhe3n {
  cx: 16px;
  cy: 14px;
  r: 2px;
  fill: currentColor;
}

.j6wc2vl1z {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8M8 16c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2m4-6c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2m4 6c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.kgneaxreo {
  cx: 8px;
  cy: 14px;
  r: 2px;
  fill: currentColor;
}

.x621cbc6b {
  cx: 12px;
  cy: 8px;
  r: 2px;
  fill: currentColor;
}

.zsfw75g9a {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8");
}

</style>
