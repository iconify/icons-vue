<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wzaoupg1b"/><path class="d-ljrzu0o"/><circle class="ec0ebxb4q"/><path class="k1esgw06w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scrubber-sharp" /></template>
<style>
.d-ljrzu0o {
  d: path("m11.02 6.8l2.46 1.4l.52.3l-.52.3l-2.46 1.4l-.52.3v-4zM2.75 19.25H8.5");
}

.ec0ebxb4q {
  cx: 10.25px;
  cy: 19.25px;
  r: 1.75px;
}

.k1esgw06w {
  d: path("M12 19.25h9.25");
}

.wzaoupg1b {
  d: path("M2.75 2.75h18.5v11.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
