<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kny-5kbex"/><path class="yspomdblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-settings-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kny-5kbex {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m0 10h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

.yspomdblm {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM16 13a1 1 0 0 1 2 0v.126c.707.182 1.344.55 1.854 1.071l.11-.063a1 1 0 0 1 1 1.732l-.109.063a4.04 4.04 0 0 1 0 2.142l.109.063A1 1 0 0 1 20.479 20h-.011a1 1 0 0 1-.504-.134l-.11-.063A4 4 0 0 1 18 20.874V21a1 1 0 0 1-2 0v-.126a3.97 3.97 0 0 1-1.854-1.071l-.11.063a1 1 0 0 1-1-1.732l.109-.063a4 4 0 0 1 0-2.142l-.109-.063a1 1 0 0 1 1-1.732l.11.063A4 4 0 0 1 16 13.126Zm1.001 2h-.002a2 2 0 0 0-1.748 1.029a2.01 2.01 0 0 0 .033 2A2 2 0 1 0 17.001 15M7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
