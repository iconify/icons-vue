<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nww2rg31f"/><path class="a44adix4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-photo-camera-front" /></template>
<style>
.a44adix4r {
  fill: currentColor;
  d: path("M20 5h-3.17L15 3H9L7.17 5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m0 14H4V7h4.05l1.83-2h4.24l1.83 2H20zm-8-6c1.1 0 2-.9 2-2s-.9-2-2-2s-2 .9-2 2s.9 2 2 2m2.78 1.58a6.95 6.95 0 0 0-5.56 0A2.01 2.01 0 0 0 8 16.43V17h8v-.57c0-.81-.48-1.53-1.22-1.85");
}

.nww2rg31f {
  fill: currentColor;
  d: path("m15.95 7l-1.83-2H9.88L8.05 7H4v12h16V7zM12 9c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m4 8H8v-.57c0-.81.48-1.53 1.22-1.85a6.95 6.95 0 0 1 5.56 0A2.01 2.01 0 0 1 16 16.43z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
