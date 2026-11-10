<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t49t4dbcb"/><path class="ha0igvbuq"/><path clip-rule="evenodd" class="d6h7pcp2h"/><path class="juh5qyy5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shepherds-hut-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d6h7pcp2h {
  fill-rule: evenodd;
  d: path("M14 7H17V3H18C18.342 3 18.677 3.03 19 3.1V23H17V21H14V23H12V3H14V7ZM14 19H17V17H14V19ZM14 15H17V13H14V15ZM14 11H17V9H14V11Z");
}

.ha0igvbuq {
  d: path("M7 17C8.657 17 10 18.34 10 20C10 21.66 8.657 23 7 23C5.343 23 4 21.66 4 20C4 18.34 5.343 17 7 17Z");
}

.juh5qyy5h {
  d: path("M6 12H3V8H6V12Z");
}

.t49t4dbcb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 18C23 18.55 22.552 19 22 19H19V23H17V21H14V23H12V19H9.826C9.937 19.31 10 19.65 10 20C10 21.66 8.657 23 7 23C5.343 23 4 21.66 4 20C4 19.65 4.063 19.31 4.174 19H2C1.448 19 1 18.55 1 18V4C1 3.45 1.448 3 2 3H6V1H8V3H18C20.761 3 23 5.24 23 8V18Z");
}

</style>
