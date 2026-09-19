<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfnzbfbfv"/><path class="ou7dwua_r"/><circle class="xyka2mboc"/><path class="j2hpy1bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-recent-actors" /></template>
<style>
.j2hpy1bxc {
  fill: currentColor;
  d: path("M8 13.4c-1.3 0-3.89.65-3.89 1.95V16h7.78v-.65c0-1.3-2.59-1.95-3.89-1.95");
}

.lfnzbfbfv {
  fill: currentColor;
  d: path("M13 7H3v10h10zM8 8c1.07 0 1.95.87 1.95 1.95c0 1.07-.87 1.95-1.95 1.95s-1.95-.87-1.95-1.95S6.93 8 8 8m3.89 8H4.11v-.65c0-1.3 2.59-1.95 3.89-1.95s3.89.65 3.89 1.95z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ou7dwua_r {
  fill: currentColor;
  d: path("M21 5h2v14h-2zm-4 0h2v14h-2zm-3 14c.55 0 1-.45 1-1V6c0-.55-.45-1-1-1H2c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1zM3 7h10v10H3z");
}

.xyka2mboc {
  cx: 8px;
  cy: 9.94px;
  r: 1.95px;
  fill: currentColor;
}

</style>
