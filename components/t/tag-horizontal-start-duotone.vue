<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q1-n5on2z"/><path class="djs1zgads"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.djs1zgads {
  d: path("M10.5 12C10.5 12.8284 9.8284 13.5 9 13.5C8.1716 13.5 7.5 12.8284 7.5 12C7.5 11.1716 8.1716 10.5 9 10.5C9.8284 10.5 10.5 11.1716 10.5 12Z");
}

.q1-n5on2z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 3C21.209139 3 23 4.790861 23 7L23 17C23 19.209139 21.209139 21 19 21L10 21C9.20435 21 8.441289 20.683929 7.87868 20.12132L1.87868 14.12132C0.707107 12.949747 0.707107 11.050253 1.87868 9.87868L7.87868 3.87868C8.441289 3.316071 9.20435 3 10 3L19 3Z");
}

</style>
