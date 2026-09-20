<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ezvv-gb9h"/><path class="uy8ov6bcw"/><path class="vor676x_s"/><path class="qjuv2ybyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tkp" /></template>
<style>
.ezvv-gb9h {
  fill: var(--svg-color--00a9ff, #00a9ff);
  d: path("m11.346 12.124l2.87-3.631a4.284 4.284 0 0 0-5.636.422a4.41 4.41 0 0 0-.396 5.708a4.29 4.29 0 0 0 5.523 1.214a4.4 4.4 0 0 0 1.98-5.354l-4.34 1.646z");
}

.ft5dv1b6b {
  fill: none;
}

.qjuv2ybyi {
  fill: var(--svg-color--ffaf14, #ffaf14);
  d: path("M18.984 4.681a9 9 0 0 0-.859-.694L16.68 5.622a5.97 5.97 0 0 1 2.186 2.726L21 7.602a8.1 8.1 0 0 0-2.016-2.916z");
}

.uy8ov6bcw {
  fill: var(--svg-color--00a9ff, #00a9ff);
  d: path("M16.68 9.62a4.4 4.4 0 0 0-1.465-1.991L12.36 11.27l4.32-1.646z");
}

.vor676x_s {
  fill: var(--svg-color--ffaf14, #ffaf14);
  d: path("m19.74 8.95l-2.104.818a6.51 6.51 0 0 1-2.952 7.93a6.346 6.346 0 0 1-8.177-1.826a6.53 6.53 0 0 1 .617-8.455a6.34 6.34 0 0 1 8.357-.586l1.425-1.764a8.56 8.56 0 0 0-9.082-.91A8.76 8.76 0 0 0 3 11.999c0 3.497 2.062 6.66 5.24 8.039a8.56 8.56 0 0 0 9.36-1.708a8.82 8.82 0 0 0 2.14-9.38");
}

</style>
