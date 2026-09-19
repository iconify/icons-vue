<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-vgmblg"/><path class="i7yzdz_hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-alarm" /></template>
<style>
.i7yzdz_hu {
  fill: currentColor;
  d: path("M12.5 8H11v6l4.75 2.85l.75-1.23l-4-2.37zm4.837-6.19l4.607 3.845l-1.28 1.535l-4.61-3.843zm-10.674 0l1.282 1.536L3.337 7.19l-1.28-1.536zM12 4a9 9 0 1 0 .001 18.001A9 9 0 0 0 12 4m0 16c-3.86 0-7-3.14-7-7s3.14-7 7-7s7 3.14 7 7s-3.14 7-7 7");
}

.qk-vgmblg {
  fill: currentColor;
  d: path("M12 6c-3.86 0-7 3.14-7 7s3.14 7 7 7s7-3.14 7-7s-3.14-7-7-7m3.75 10.85L11 14V8h1.5v5.25l4 2.37z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
