<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ic-371bqb"><path class="g-flxwbkg"/><ellipse class="iqsqdf5ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:question-mark" /></template>
<style>
.g-flxwbkg {
  d: path("M30.2 2.1C18.6 2.8 12.5 9.4 12 21.3h11.7c.1-4.1 2.5-7.2 6.7-7.7c4.2-.4 8.2.6 9.4 3.4c1.3 3.1-1.6 6.7-3 8.2c-2.6 2.8-6.8 4.9-9 7.9c-2.1 3-2.5 6.9-2.7 11.7h10.3c.1-3.1.3-6 1.7-7.9c2.3-3.1 5.7-4.5 8.5-7c2.7-2.3 5.6-5.1 6-9.5C53.3 7.5 42.7 1.3 30.2 2.1");
}

.ic-371bqb {
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.iqsqdf5ym {
  cx: 30.5px;
  cy: 55.6px;
  rx: 6.5px;
  ry: 6.4px;
}

</style>
