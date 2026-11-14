<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5fsdvbqu"/><path class="f9q_2eb8k"/><path class="q-hew2bvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radiology-department" /></template>
<style>
.f9q_2eb8k {
  fill: currentColor;
  d: path("M12.75 8L14 5.75A3.75 3.75 0 0 1 15.75 9h-2.5a1.25 1.25 0 0 0-.5-1Zm0 2L14 12.25a3.75 3.75 0 0 1-3.75 0L11.5 10a1.25 1.25 0 0 0 1.25 0Zm-2-1h-2.5A3.75 3.75 0 0 1 10 5.75L11.5 8a1.25 1.25 0 0 0-.75 1Z");
}

.q-hew2bvf {
  d: path("M16 15.5h.01");
}

.q5fsdvbqu {
  d: path("M5 21.5v-17c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2v17m-16.5 0h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
