<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jqhawur8g"/><path class="rb4uotblq"/><path class="nhhp_8bzq"/><path class="q5t_ztsop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:microphone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jqhawur8g {
  fill-rule: evenodd;
  d: path("M7.5 4.5a2.5 2.5 0 0 1 5 0v4a2.5 2.5 0 0 1-5 0z");
}

.nhhp_8bzq {
  d: path("M9.036 13.5h2V18h-2z");
}

.q5t_ztsop {
  d: path("M14 8a1 1 0 1 1 2 0v1.8c0 2.914-2.721 5.2-6 5.2s-6-2.286-6-5.2V8a1 1 0 0 1 2 0v1.8c0 1.725 1.756 3.2 4 3.2s4-1.475 4-3.2z");
}

.rb4uotblq {
  d: path("M10 18.5c-2.834 0-4.5-.208-4.5-1s1.666-1 4.5-1s4.5.208 4.5 1s-1.666 1-4.5 1");
}

</style>
