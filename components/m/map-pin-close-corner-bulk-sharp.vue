<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ooj7xybof"/><path class="f_pzkgdpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-close-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f_pzkgdpw {
  d: path("M7.236 7.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414M17 15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L18.414 17l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 18.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L15.586 17l-2.293-2.293a.999.999 0 1 1 1.414-1.414Z");
}

.ooj7xybof {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.567 17.929l.423 2.928a1.001 1.001 0 0 1-1.545.975c-1.854-1.237-3.557-2.817-4.876-4.616a14 14 0 0 1-1.832-3.314A10.9 10.9 0 0 1 2 10a7.98 7.98 0 0 1 2.343-5.657A8.002 8.002 0 0 1 17.98 9.43a1 1 0 0 1-.995 1.07a6.492 6.492 0 0 0-6.418 7.429");
}

</style>
