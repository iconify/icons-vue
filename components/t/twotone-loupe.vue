<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxiqy3mmh"/><path class="hi3nt2zxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-loupe" /></template>
<style>
.hi3nt2zxt {
  fill: currentColor;
  d: path("M11 17h2v-4h4v-2h-4V7h-2v4H7v2h4zm1 5h8c1.1 0 2-.9 2-2v-8c0-5.51-4.49-10-10-10S2 6.49 2 12s4.49 10 10 10m0-18c4.41 0 8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8s3.59-8 8-8");
}

.xxiqy3mmh {
  fill: currentColor;
  d: path("M12 20c4.41 0 8-3.59 8-8s-3.59-8-8-8s-8 3.59-8 8s3.59 8 8 8m-5-9h4V7h2v4h4v2h-4v4h-2v-4H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
