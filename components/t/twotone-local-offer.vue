<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzkx2qbgp"/><path class="oqb-de-al"/><circle class="k79q3xboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-offer" /></template>
<style>
.k79q3xboj {
  cx: 6.5px;
  cy: 6.5px;
  r: 1.5px;
  fill: currentColor;
}

.oqb-de-al {
  fill: currentColor;
  d: path("M12.41 2.58C12.05 2.22 11.55 2 11 2H4c-1.1 0-2 .9-2 2v7c0 .55.22 1.05.59 1.42l9 9c.36.36.86.58 1.41.58s1.05-.22 1.41-.59l7-7c.37-.36.59-.86.59-1.41s-.23-1.06-.59-1.42zM13 20.01L4 11V4h7v-.01l9 9z");
}

.wzkx2qbgp {
  fill: currentColor;
  d: path("M11 4H4v7l9 9.01L20 13zM6.5 8C5.67 8 5 7.33 5 6.5S5.67 5 6.5 5S8 5.67 8 6.5S7.33 8 6.5 8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
