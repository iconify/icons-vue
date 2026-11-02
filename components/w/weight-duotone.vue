<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bi2-9n95m"/><path class="bk9ymdf4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-duotone" /></template>
<style>
.bi2-9n95m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 7c.732 0 1.416.341 1.927.852c.523.523.865 1.192 1.043 1.905l2 8c.253 1.014.015 2.242-.87 2.883c-.321.233-.703.36-1.1.36H6c-.397 0-.779-.127-1.1-.36c-.885-.641-1.123-1.869-.87-2.883l2-8c.178-.713.52-1.382 1.043-1.905C7.584 7.341 8.268 7 9 7Z");
}

.bk9ymdf4p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h3c.882 0 1.706.825 2 2l2 8c.254 1.016-.238 2-1 2H6c-.762 0-1.254-.984-1-2l2-8c.294-1.175 1.118-2 2-2zm0 0a2 2 0 1 1 0-4m0 0a2 2 0 1 1 0 4");
}

.ft5dv1b6b {
  fill: none;
}

</style>
