<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a9ypr5fux"/><path class="xii-u1kii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-dot-duotone" /></template>
<style>
.a9ypr5fux {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.7909 3.7909 2 6 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xii-u1kii {
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12Z");
}

</style>
