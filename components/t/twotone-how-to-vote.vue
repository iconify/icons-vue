<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-6wk6kzu"/><path class="hiy0gkbow"/><path class="ypo7z-bvb"/><path class="em-56sbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-how-to-vote" /></template>
<style>
.em-56sbac {
  fill: currentColor;
  d: path("M19.11 7.25L14.16 2.3a.975.975 0 0 0-1.4-.01L6.39 8.66a.996.996 0 0 0 0 1.41l4.95 4.95c.39.39 1.02.39 1.41 0l6.36-6.36a.996.996 0 0 0 0-1.41m-7.06 5.65L8.51 9.36l4.95-4.95L17 7.95z");
}

.hiy0gkbow {
  fill: currentColor;
  d: path("M18 13h-.68l-2 2h1.91L19 17H5l1.78-2h2.05l-2-2H6l-3 3v4c0 1.1.89 2 1.99 2H19a2 2 0 0 0 2-2v-4zm1 7H5v-1h14z");
}

.n-6wk6kzu {
  fill: currentColor;
  d: path("M5 19h14v1H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ypo7z-bvb {
  fill: currentColor;
  d: path("M12.048 12.905L8.505 9.362l4.95-4.95l3.543 3.543z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
