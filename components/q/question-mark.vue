<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="n1lsf0bnc"><path class="xsfn84bsi"/><ellipse class="n910ocbpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:question-mark" /></template>
<style>
.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.n910ocbpr {
  cx: 30.515px;
  cy: 55.567px;
  rx: 6.532px;
  ry: 6.433px;
}

.xsfn84bsi {
  d: path("M30.249 2.065C18.612 2.789 12.531 9.379 12 21.296h11.739c.147-4.128 2.451-7.214 6.741-7.669c4.211-.447 8.206.556 9.416 3.435c1.307 3.11-1.627 6.724-3.022 8.241c-2.582 2.813-6.776 4.865-8.95 7.9c-2.131 2.974-2.51 6.887-2.674 11.676h10.346c.145-3.062.349-5.995 1.742-7.898c2.266-3.092 5.65-4.541 8.486-6.983c2.709-2.334 5.559-5.147 6.043-9.501C53.32 7.466 42.683 1.289 30.249 2.065");
}

</style>
