<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc50cvs0o"/><path class="i601mue2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-cursor" /></template>
<style>
.cc50cvs0o {
  d: path("M6 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3Z");
}

.i601mue2m {
  d: path("M9.88767 16.6457L7.02471 7.66244C6.89855 7.26656 7.27689 6.89543 7.6725 7.02702L16.6515 10.0135C17.0987 10.1623 17.1212 10.7838 16.6859 10.9643L12.9526 12.5116C12.8352 12.5602 12.7403 12.6508 12.6865 12.7654L10.8359 16.7071C10.6392 17.1262 10.0282 17.0866 9.88767 16.6457Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
