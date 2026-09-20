<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGiY9Mlbak)" clip-rule="evenodd" class="t7jp-sybk"/><defs><linearGradient id="SVGiY9Mlbak" x1="5.634" x2="16.474" y1="4.44" y2="16.349" gradientUnits="userSpaceOnUse"><stop class="k-28254fe"/><stop offset=".807" class="hmyot6bsg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trias" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hmyot6bsg {
  stop-color: var(--svg-color--12aba9, #12aba9);
}

.k-28254fe {
  stop-color: var(--svg-color--79dce5, #79dce5);
}

.t7jp-sybk {
  fill-rule: evenodd;
  d: path("M13.396 3.085a.42.42 0 0 0-.563.053L3.65 13.756a.35.35 0 0 0 .076.527l9.847 6.647c.15.101.357.092.497-.023l6.235-5.163a.35.35 0 0 0 .118-.373L17.74 6.443zm-8.95 10.73l9.645.873l.695-6.262l-1.832-4.449zm9.578 1.482l-8.865-.803l8.33 5.622zm.656.059l4.6.416l-5.115 4.236zm5.004-.162l-4.936-.447l.675-6.085l1.836-1.541zm-2.781-8.6l-1.609 1.35l-1.568-3.806z");
}

</style>
