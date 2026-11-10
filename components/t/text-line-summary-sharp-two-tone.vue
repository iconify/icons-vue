<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zmqy9-k_j"/><path clip-rule="evenodd" class="d23ondp6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-line-summary-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d23ondp6d {
  fill-rule: evenodd;
  d: path("M22 9H6V7H22V9ZM22 4H6V2H22V4ZM15 14H6V12H15V14Z");
}

.zmqy9-k_j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 17.75H18.471L17.6 16.93L18.968 15.47L21.684 18.02C21.885 18.21 22 18.47 22 18.75C22 19.03 21.885 19.29 21.684 19.48L18.995 22L17.628 20.54L18.472 19.75H3C2.448 19.75 2 19.3 2 18.75V2H4V17.75Z");
}

</style>
