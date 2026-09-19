<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il07cg1zu"/><path class="umpdgcc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-photo-camera" /></template>
<style>
.il07cg1zu {
  fill: currentColor;
  d: path("M20 6h-4.05l-1.83-2H9.88L8.05 6H4v12h16zm-8 11c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.umpdgcc7x {
  fill: currentColor;
  d: path("M4 20h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2h-3.17L15 2H9L7.17 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2M4 6h4.05l1.83-2h4.24l1.83 2H20v12H4zm8 1c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m0 8c-1.65 0-3-1.35-3-3s1.35-3 3-3s3 1.35 3 3s-1.35 3-3 3");
}

</style>
