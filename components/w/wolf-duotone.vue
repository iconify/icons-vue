<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fv1d54lsh"/><path class="t7ftxy1my"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fv1d54lsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m20.414 13l1.293 1.293a1 1 0 0 1-.336 1.635l-4.647 1.859l-.83 1.66C15.357 20.522 14.348 21.999 13 22h-2c-1.348-.001-2.357-1.478-2.894-2.553l-.83-1.66l-4.647-1.859a1 1 0 0 1-.336-1.635L3.586 13l-1.293-1.293a1 1 0 0 1 0-1.414l1-1C3.605 8.98 4 8.468 4 8V4a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l2 2C9.02 5.605 9.532 6 10 6h4c.468 0 .98-.395 1.293-.707l2-2c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v4c0 .468.395.98.707 1.293l1 1a1 1 0 0 1 0 1.414Z");
}

.t7ftxy1my {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m21 11l-2 2l2 2l-5 2l-1 2c-.613 1.226-1.387 2-2 2h-2c-.613 0-1.387-.774-2-2l-1-2l-5-2l2-2l-2-2l1-1c.64-.64 1-1.36 1-2V4c0-.369.631-.369 1 0l2 2c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l2-2c.369-.369 1-.369 1 0v4c0 .64.36 1.36 1 2zM9 11l1 1m5-1l-1 1m-2 6h.01");
}

</style>
