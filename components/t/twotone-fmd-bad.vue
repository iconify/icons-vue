<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvt_p2blf"/><path class="ybyd9j4hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fmd-bad" /></template>
<style>
.mvt_p2blf {
  fill: currentColor;
  d: path("M11 15h2v-2h-2zm0-4h2V6h-2zm1-9c-4.2 0-8 3.22-8 8.2c0 3.32 2.67 7.25 8 11.8c5.33-4.55 8-8.48 8-11.8C20 5.22 16.2 2 12 2m0 17.33c-4.05-3.7-6-6.79-6-9.14C6 6.57 8.65 4 12 4s6 2.57 6 6.2c0 2.34-1.95 5.44-6 9.13");
}

.ybyd9j4hh {
  fill: currentColor;
  d: path("M12 19.33c4.05-3.7 6-6.79 6-9.14C18 6.57 15.35 4 12 4s-6 2.57-6 6.2c0 2.34 1.95 5.44 6 9.13M11 6h2v5h-2zm0 7h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
