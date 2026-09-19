<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_wdrlbfv"/><path class="inq22acyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-next-week" /></template>
<style>
.inq22acyd {
  fill: currentColor;
  d: path("m11 18.5l4-4l-4-4l-1 1l3 3l-3 3zM20 7h-4V5c0-.55-.22-1.05-.59-1.41C15.05 3.22 14.55 3 14 3h-4c-1.1 0-2 .9-2 2v2H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2M10 5h4v2h-4zm10 15H4V9h16z");
}

.p_wdrlbfv {
  fill: currentColor;
  d: path("M4 20h16V9H4zm6-8.5l1-1l4 4l-4 4l-1-1l3-3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
