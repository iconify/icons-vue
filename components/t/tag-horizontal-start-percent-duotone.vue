<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ak-drqc-a"/><path class="es_f_abip"/><path class="qg4ud0b0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-percent-duotone" /></template>
<style>
.ak-drqc-a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 3C21.209139 3 23 4.790861 23 7L23 17C23 19.209139 21.209139 21 19 21L10 21C9.20435 21 8.441289 20.683929 7.87868 20.12132L1.87868 14.12132C0.707107 12.949747 0.707107 11.050253 1.87868 9.87868L7.87868 3.87868C8.441289 3.316071 9.20435 3 10 3L19 3Z");
  stroke: none;
}

.es_f_abip {
  d: path("M11.25 15L17.25 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qg4ud0b0f {
  fill: currentColor;
  d: path("M12.75 8.5C12.75 9.3284 12.0784 10 11.25 10C10.4216 10 9.75 9.3284 9.75 8.5C9.75 7.6716 10.4216 7 11.25 7C12.0784 7 12.75 7.6716 12.75 8.5ZM18.75 15.5C18.75 16.3284 18.0784 17 17.25 17C16.4216 17 15.75 16.3284 15.75 15.5C15.75 14.6716 16.4216 14 17.25 14C18.0784 14 18.75 14.6716 18.75 15.5Z");
  stroke: none;
}

</style>
