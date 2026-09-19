<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jtac1ebya"/><path class="zt_nthbkb"/><path class="pixq-omwy"/><path class="wgidj_bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:mobile-phone" /></template>
<style>
.jtac1ebya {
  fill: var(--svg-color--405866, #405866);
  d: path("M47.873 0H16.124a5.08 5.08 0 0 0-5.08 5.079v53.845a5.084 5.084 0 0 0 5.08 5.079h31.749a5.09 5.09 0 0 0 5.083-5.079V5.087A5.085 5.085 0 0 0 47.873.008");
}

.pixq-omwy {
  fill: var(--svg-color--28a6de, #28a6de);
  d: path("M31.3 3.876H19.425a4.03 4.03 0 0 0-4.03 4.02v42.667a4.03 4.03 0 0 0 4.03 4.02h25.16c.813 0 1.564-.249 2.196-.659C36.084 39.99 30.358 21.259 31.303 3.874");
}

.wgidj_bqv {
  fill: var(--svg-color--cbd5dc, #cbd5dc);
  d: path("M35.3 59.39c0 1.817-1.476 3.298-3.297 3.298s-3.297-1.48-3.297-3.298s1.476-3.298 3.297-3.298s3.297 1.48 3.297 3.298m-12.705 0a2.412 2.412 0 1 1-4.823.003a2.412 2.412 0 0 1 4.823-.003m18.815 0a2.412 2.412 0 1 0 4.822 0a2.41 2.41 0 0 0-4.822 0");
}

.zt_nthbkb {
  fill: var(--svg-color--85cfea, #85cfea);
  d: path("M44.579 3.876h-25.16a4.03 4.03 0 0 0-4.03 4.02v42.667a4.03 4.03 0 0 0 4.03 4.02h25.16c2.22 0 4.02-1.81 4.02-4.02V7.892c0-2.22-1.805-4.02-4.02-4.02");
}

</style>
