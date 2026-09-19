<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcmg71b3w"/><path class="g8a-6xbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-ballot" /></template>
<style>
.g8a-6xbac {
  fill: currentColor;
  d: path("M13 7.5h5v2h-5zm0 7h5v2h-5zM19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zM11 6H6v5h5zm-1 4H7V7h3zm1 3H6v5h5zm-1 4H7v-3h3z");
}

.xcmg71b3w {
  fill: currentColor;
  d: path("M7 14h3v3H7zm0-7h3v3H7zM5 19h14V5H5zm8-11.5h5v2h-5zm0 7h5v2h-5zM6 6h5v5H6zm0 7h5v5H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
