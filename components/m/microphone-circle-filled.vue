<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG1RnJWbnN"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="bl5p84b6v"/><path class="bf7aa54lr"/><path class="wdtp5v6tc"/><path class="o9esqkd2g"/></g></mask></defs><circle mask="url(#SVG1RnJWbnN)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:microphone-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bf7aa54lr {
  d: path("M13 21.5c-2.834 0-4.5-.208-4.5-1s1.666-1 4.5-1s4.5.208 4.5 1s-1.666 1-4.5 1");
}

.bl5p84b6v {
  fill-rule: evenodd;
  d: path("M10.5 7.5a2.5 2.5 0 0 1 5 0v4a2.5 2.5 0 0 1-5 0z");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.o9esqkd2g {
  d: path("M17 11a1 1 0 1 1 2 0v1.8c0 2.914-2.721 5.2-6 5.2s-6-2.286-6-5.2V11a1 1 0 0 1 2 0v1.8c0 1.725 1.756 3.2 4 3.2s4-1.475 4-3.2z");
}

.wdtp5v6tc {
  d: path("M12.036 16.5h2V21h-2z");
}

</style>
