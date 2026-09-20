<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="weqt_hb_s"/><path class="fota-ezzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shopsy" /></template>
<style>
.fota-ezzu {
  d: path("M23.962 43.488H11.058c-4.411.266-4.082-4.148-4.082-4.148l3.487-24.67c.266-3.614 3.344-3.482 3.344-3.482l3.718-.003s-1.267-6.421 6.27-6.684s.482 0 .482 0h-.554h.483c7.536.263 6.269 6.683 6.269 6.683l3.718.005s3.079-.133 3.344 3.48l3.487 24.67s.33 4.415-4.082 4.15h-12.98Z");
}

.weqt_hb_s {
  d: path("M17.915 35.5c1.35 1.135 2.81 1.655 6.085 1.655h1.66a4.897 4.897 0 0 0 4.891-4.902a4.897 4.897 0 0 0-4.891-4.902h-3.32a4.897 4.897 0 0 1-4.891-4.902a4.897 4.897 0 0 1 4.891-4.902H24c3.276 0 4.734.52 6.085 1.654m-14.099-8.017h15.577");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
