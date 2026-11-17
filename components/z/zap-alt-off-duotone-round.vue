<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j8oyly1nm"/><path class="snv8479xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j8oyly1nm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.5 12.5L8.769 5.769l.703-1.581A2 2 0 0 1 11.3 3H15a1.16 1.16 0 0 1 1.008 1.736l-2.016 3.528A1.16 1.16 0 0 0 15 10h1a.828.828 0 0 1 .586 1.414Zm-7.086 7.086a.583.583 0 0 1-.98-.538l1.241-5.584A1.205 1.205 0 0 0 7.5 12a.98.98 0 0 1-.818-.443a.98.98 0 0 1-.073-.928l.314-.706L12.5 15.5Z");
}

.snv8479xh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12.5 15.5l-4.086 4.086c-.412.412-1.107.03-.98-.538l1.24-5.584A1.203 1.203 0 0 0 7.5 12a.975.975 0 0 1-.89-1.37l.313-.707M8.77 5.77l.703-1.581A2 2 0 0 1 11.3 3H15c.891 0 1.45.963 1.008 1.736l-2.016 3.528A1.16 1.16 0 0 0 15 10h1a.828.828 0 0 1 .586 1.414L16 12M2 5l17 17");
}

</style>
