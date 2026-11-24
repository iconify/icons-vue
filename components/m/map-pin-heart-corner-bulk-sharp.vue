<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ooj7xybof"/><path class="d7usngb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-heart-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d7usngb_d {
  d: path("M7 9a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8 5.398a3.7 3.7 0 0 1 2.375-.898c1.468 0 2.625.986 2.625 2.5c-.001 1.964-2.294 3.6-3.871 4.52q-.335.198-.682.374a1 1 0 0 1-.894 0A15.4 15.4 0 0 1 14.4 19.55c-1.103-.828-2.399-2.058-2.4-3.55c0-1.514 1.157-2.5 2.625-2.5c.869 0 1.718.335 2.375.898");
}

.ooj7xybof {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.567 17.929l.423 2.928a1.001 1.001 0 0 1-1.545.975c-1.854-1.237-3.557-2.817-4.876-4.616a14 14 0 0 1-1.832-3.314A10.9 10.9 0 0 1 2 10a7.98 7.98 0 0 1 2.343-5.657A8.002 8.002 0 0 1 17.98 9.43a1 1 0 0 1-.995 1.07a6.492 6.492 0 0 0-6.418 7.429");
}

</style>
