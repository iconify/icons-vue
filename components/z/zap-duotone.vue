<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bo_uaabdg"/><path class="k403qyi5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duotone" /></template>
<style>
.bo_uaabdg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.293 3.293c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v6h4c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-8 8a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 9 20v-6H5a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635Z");
}

.ft5dv1b6b {
  fill: none;
}

.k403qyi5l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 8l-4 4c-.369.369-.369 1 0 1h4a1 1 0 0 1 1 1v6c0 .369.631.369 1 0l8-8c.369-.369.369-1 0-1h-4a1 1 0 0 1-1-1V4c0-.369-.631-.369-1 0z");
}

</style>
