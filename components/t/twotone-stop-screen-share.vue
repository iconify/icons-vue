<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx34og72k"/><path class="n2r_kzb3p"/><path class="nniocn02s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-stop-screen-share" /></template>
<style>
.dx34og72k {
  fill: currentColor;
  d: path("M10.67 12.54C9.13 12.92 7.96 13.71 7 15c.31-1.48.94-2.93 2.08-4.05L4.13 6.02H4v10.01h10.14z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.n2r_kzb3p {
  fill: currentColor;
  d: path("m21.79 18l2 2H24v-2zM1.11 2.98l1.55 1.56c-.41.37-.66.89-.66 1.48V16c0 1.1.9 2 2.01 2H0v2h18.13l2.71 2.71l1.41-1.41L2.52 1.57zM4 6.02h.13l4.95 4.93C7.94 12.07 7.31 13.52 7 15c.96-1.29 2.13-2.08 3.67-2.46l3.46 3.48H4zm16 0v10.19l1.3 1.3c.42-.37.7-.89.7-1.49v-10a2 2 0 0 0-2-2H7.8l2 2zm-7.07 3.13l2.79 2.78l1.28-1.2L13 7v2.13z");
}

.nniocn02s {
  fill: currentColor;
  d: path("M20 6.02H9.8l3.13 3.13c.02 0 .04-.01.07-.02V7l4 3.73l-1.28 1.2L20 16.21z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
