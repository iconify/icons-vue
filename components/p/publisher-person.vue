<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sc7su9bqa"/><path class="yhdvh645q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:publisher-person" /></template>
<style>
.sc7su9bqa {
  d: path("M8.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM4 21.5c0-5 3.5-8.5 8-8.5s8 3.5 8 8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhdvh645q {
  d: path("M12 17q-1.125-1.125-3-.75v4q1.875-.375 3 .75q1.125-1.125 3-.75v-4q-1.875-.375-3 .75Zm0 0v4");
}

</style>
