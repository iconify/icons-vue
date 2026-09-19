<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lc7mkuvlr"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:one-oclock" /></template>
<style>
.lc7mkuvlr {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m4 30c0 1.477-.81 2.752-2 3.445V38h-4v-.314l-3-1.613l1.427-2.308A4 4 0 0 1 28 32c0-1.477.81-2.752 2-3.445V6h4v18.756L39.416 16L43 17.934l-7.513 12.143c.317.573.513 1.222.513 1.923");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
