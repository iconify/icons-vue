<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuaj1zxbd"/><path class="vy2urf6aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-brightness-3" /></template>
<style>
.vy2urf6aa {
  fill: currentColor;
  d: path("M9 2c-1.05 0-2.05.16-3 .46c4.06 1.27 7 5.06 7 9.54s-2.94 8.27-7 9.54c.95.3 1.95.46 3 .46c5.52 0 10-4.48 10-10S14.52 2 9 2m3.7 17.09c1.46-2 2.3-4.46 2.3-7.09s-.84-5.09-2.3-7.09A8 8 0 0 1 17 12a8 8 0 0 1-4.3 7.09");
}

.yuaj1zxbd {
  fill: currentColor;
  d: path("M12.7 4.91c1.46 2 2.3 4.46 2.3 7.09s-.84 5.09-2.3 7.09A8 8 0 0 0 17 12a8 8 0 0 0-4.3-7.09");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
