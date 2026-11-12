<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8i3b9xno"/><path class="xbxy7ib5r"/><path class="c0tgf1saz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-2-bold-duotone" /></template>
<style>
.c0tgf1saz {
  fill: currentColor;
  d: path("M12.25 14.5359V2C12.25 3.60747 12.8119 5.08371 13.75 6.243V18C13.75 16.6339 13.1733 15.4024 12.25 14.5359Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x8i3b9xno {
  fill: currentColor;
  d: path("M9 13.25C11.6234 13.25 13.75 15.3766 13.75 18C13.75 20.6234 11.6234 22.75 9 22.75C6.37665 22.75 4.25 20.6234 4.25 18C4.25 15.3766 6.37665 13.25 9 13.25Z");
}

.xbxy7ib5r {
  fill: currentColor;
  d: path("M13 1.25C13.4142 1.25 13.75 1.58579 13.75 2C13.75 4.8995 16.1005 7.25 19 7.25C19.4142 7.25 19.75 7.58579 19.75 8C19.75 8.41421 19.4142 8.75 19 8.75C15.2721 8.75 12.25 5.72792 12.25 2C12.25 1.58579 12.5858 1.25 13 1.25Z");
}

</style>
