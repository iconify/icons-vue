<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":307};
const content = `<g class="bi12bsetm"><path class="rfgm5wfky"/><path class="zv5jzbpac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:sitepoint" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.rfgm5wfky {
  fill: var(--svg-color--07508b, #07508b);
  d: path("m249.63 171.958l-22.595-21.6l-71.426-65.624l-30.791 29.24c-2.815 3.83-2.624 9 .574 12.581l28.15 24.243l-.097.038l30.256 28.915c3.58 3.983 3.485 9.881-.268 13.71l-81.575 77.516l37.092 35.406l110.68-105.166c8.484-8.08 8.503-21.179 0-29.298z");
}

.zv5jzbpac {
  fill: var(--svg-color--e57b25, #e57b25);
  d: path("m6.343 134.464l22.596 21.543l71.464 65.623l30.772-29.24a9.965 9.965 0 0 0-.574-12.581l-28.15-24.281l.096-.058l-30.274-28.895c-3.543-3.964-3.447-9.881.287-13.692l81.575-77.553L117.043 0L6.363 105.166c-8.484 8.08-8.484 21.198 0 29.298z");
}

</style>
