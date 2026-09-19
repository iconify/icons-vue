<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="tzvfjcbcx"><path class="d42zawbjb"/><circle class="efdrmjb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:sparkle" /></template>
<style>
.d42zawbjb {
  d: path("M32 25.4c1.1 0 4.4-15.5 4.5-19.8c.1-2-2-3.7-4.5-3.7s-4.6 1.6-4.5 3.7c.2 4.3 3.4 19.8 4.5 19.8M25.4 32c0-1.1-15.5-4.4-19.8-4.5c-2-.1-3.7 2-3.7 4.5s1.6 4.6 3.7 4.5c4.3-.2 19.8-3.4 19.8-4.5m2-7.3L10.3 10.3l14.5 17.1c.7-1 1.6-1.9 2.6-2.7m9.2 14.6l17.1 14.5l-14.4-17.2q-1.2 1.5-2.7 2.7m21.7-11.8c-4.3.1-19.8 3.4-19.8 4.5s15.5 4.3 19.8 4.5c2 .1 3.7-2 3.7-4.5s-1.6-4.6-3.7-4.5M32 38.6c-1.1 0-4.3 15.5-4.5 19.8c-.1 2 2 3.7 4.5 3.7s4.6-1.6 4.5-3.7c-.1-4.3-3.4-19.8-4.5-19.8m7.3-11.2l14.5-17.1l-17.2 14.4q1.5 1.2 2.7 2.7m-14.6 9.2L10.3 53.7l17.1-14.5c-1-.7-1.9-1.6-2.7-2.6");
}

.efdrmjb9n {
  cx: 32px;
  cy: 32px;
  r: 4.5px;
}

.tzvfjcbcx {
  fill: var(--svg-color--c28fef, #c28fef);
}

</style>
