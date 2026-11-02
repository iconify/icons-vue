<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mcg_oib0e"/><path class="scc1kvjkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mcg_oib0e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.828 15.586L8.414 7.172l3.879-3.879c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v6h4c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635Zm-2.121 2.121l-3 3a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 9 20v-6H5a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l2-2Z");
}

.scc1kvjkf {
  d: path("m2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-17-17a.999.999 0 1 1 1.414-1.414");
}

</style>
