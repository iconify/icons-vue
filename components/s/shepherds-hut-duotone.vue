<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t8645yeum"/><path class="g9h15tbcq"/><path clip-rule="evenodd" class="gsr2ufb1j"/><path class="or9ve5osy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shepherds-hut-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9h15tbcq {
  d: path("M7 17C8.6569 17 10 18.34 10 20C10 21.66 8.6569 23 7 23C5.3431 23 4 21.66 4 20C4 18.34 5.3431 17 7 17Z");
}

.gsr2ufb1j {
  fill-rule: evenodd;
  d: path("M14 7H17V3H18C18.3424 3 18.6769 3.03 19 3.1V22C19 22.55 18.5523 23 18 23C17.4477 23 17 22.55 17 22V21H14V22C14 22.55 13.5523 23 13 23C12.4477 23 12 22.55 12 22V3H14V7ZM14 19H17V17H14V19ZM14 15H17V13H14V15ZM14 11H17V9H14V11Z");
}

.or9ve5osy {
  d: path("M4.5 8C5.3284 8 6 8.67 6 9.5V10.5C6 11.33 5.3284 12 4.5 12H3V8H4.5Z");
}

.t8645yeum {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 16C23 17.66 21.6569 19 20 19H19V22C19 22.55 18.5523 23 18 23C17.4477 23 17 22.55 17 22V21H14V22C14 22.55 13.5523 23 13 23C12.4477 23 12 22.55 12 22V19H9.8262C9.9369 19.31 10 19.65 10 20C10 21.66 8.6569 23 7 23C5.3431 23 4 21.66 4 20C4 19.65 4.0631 19.31 4.1738 19C2.5169 19 1 17.66 1 16V6C1 4.34 2.3431 3 4 3H6V2C6 1.45 6.4477 1 7 1C7.5523 1 8 1.45 8 2V3H18C20.7614 3 23 5.24 23 8V16Z");
}

</style>
