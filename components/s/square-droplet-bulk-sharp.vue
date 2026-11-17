<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="rslbp_bkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-droplet-bulk-sharp" /></template>
<style>
.bpp7y5g_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rslbp_bkc {
  d: path("M12.581 7.186c.193.138.376.29.556.444c.954.818 1.817 1.793 2.382 2.923c.363.725.592 1.521.592 2.336a4.11 4.11 0 0 1-7.899 1.6c-.864-2.045.117-4.145 1.48-5.703a11.5 11.5 0 0 1 1.727-1.6a1 1 0 0 1 1.162 0M12 9.292c-.973.872-2.111 2.228-2.111 3.597a2.11 2.11 0 1 0 4.222 0c0-1.369-1.138-2.725-2.111-3.597");
}

</style>
