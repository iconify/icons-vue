<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kb_joubbb"/><path class="pbcs86a_f"/><path class="t-bdwis-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-fast-duotone" /></template>
<style>
.kb_joubbb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.9589 2.2837L18.4511 17.5197C18.1997 18.3694 17.4193 18.9523 16.5332 18.9523C15.8723 18.9523 15.2541 18.6258 14.8815 18.08L11.4582 13.0658C11.3177 12.86 11.14 12.6823 10.9342 12.5418L5.92 9.1185C5.3742 8.7459 5.0477 8.1277 5.0477 7.4668C5.0477 6.5807 5.6306 5.8003 6.4803 5.5489L21.7163 1.0411C21.8084 1.0138 21.9039 1 22 1C22.5523 1 23 1.4477 23 2C23 2.0961 22.9862 2.1916 22.9589 2.2837Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pbcs86a_f {
  fill: currentColor;
  d: path("M22.7071 1.2929C22.8946 1.4804 23 1.7348 23 2C23 2.0961 22.9862 2.1916 22.9589 2.2837L18.4511 17.5197C18.1997 18.3694 17.4193 18.9523 16.5332 18.9523C15.8723 18.9523 15.2541 18.6258 14.8815 18.08L11.4582 13.0658C11.3881 12.9632 11.3086 12.8672 11.2207 12.7793L22.7071 1.2929Z");
  stroke: none;
}

.t-bdwis-p {
  d: path("M2 22L6.5 17.5M2 16L5.5 12.5M8 22L11.5 18.5");
}

</style>
