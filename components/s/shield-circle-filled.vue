<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG7scR3WZK"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="h35crg_jx"/></mask></defs><circle mask="url(#SVG7scR3WZK)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:shield-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.h35crg_jx {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M14.335 6.03a3 3 0 0 0-2.67 0L8.029 7.836c-.95.472-1.537 1.374-1.528 2.344c.016 1.774.21 4.03.9 5.477c.766 1.607 2.65 3.272 4.216 4.44c.83.619 1.936.619 2.766 0c1.566-1.168 3.45-2.833 4.216-4.44c.69-1.447.884-3.703.9-5.477c.009-.97-.579-1.872-1.528-2.344zm-3.56-1.791a5 5 0 0 1 4.45 0l3.636 1.806c1.552.772 2.654 2.329 2.638 4.153c-.016 1.785-.197 4.439-1.095 6.32c-.998 2.094-3.254 4.01-4.825 5.183a4.29 4.29 0 0 1-5.158 0c-1.571-1.172-3.827-3.09-4.825-5.183c-.898-1.881-1.079-4.535-1.095-6.32c-.016-1.824 1.086-3.381 2.638-4.153z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
