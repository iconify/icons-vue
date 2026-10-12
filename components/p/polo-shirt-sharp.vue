<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d9igfccyv"/><path class="ikfe4gbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:polo-shirt-sharp" /></template>
<style>
.d9igfccyv {
  d: path("M7.87 3.73L3.63 6.02l-.88.48l.4.92l.95 2.16l.4.92l.94-.35l.12-.05l.94-.35v11h11v-11l.94.35l.12.05l.94.35l.4-.92l.95-2.16l.4-.92l-.88-.48l-4.24-2.29l-.88-.48l-.85.52l-1.55.96l-.85.52l-.85-.52l-1.55-.96l-.85-.52z");
}

.ikfe4gbvz {
  d: path("m9.18 3.51l2.39 1.48l.43.26l-.33.37l-1.34 1.51l-.33.37l-.35-.35L8.1 5.6l-.35-.35l.22-.45l.56-1.1l.22-.45zm3.15 2.11l1.34 1.51l.33.37l.35-.35L15.9 5.6l.35-.35l-.22-.45l-.56-1.1l-.22-.45l-.43.26l-2.39 1.48l-.43.26zM12 8v3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
