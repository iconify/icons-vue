<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bnwdp6j8x"/><path class="cedz78ber"/><path clip-rule="evenodd" class="t6q869exz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:speakers-duotone" /></template>
<style>
.bnwdp6j8x {
  stroke-opacity: 0.4;
  d: path("M4 4.1716C2.8015 4.5954 2 5.7286 2 7V17C2 18.2714 2.8015 19.4046 4 19.8284");
}

.cedz78ber {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 15.0001C19 17.2092 17.2091 19.0001 15 19.0001C12.7909 19.0001 11 17.2092 11 15.0001C11 12.791 12.7909 11.0001 15 11.0001C17.2091 11.0001 19 12.791 19 15.0001ZM17 15.0001C17 13.8955 16.1046 13.0001 15 13.0001C13.8954 13.0001 13 13.8955 13 15.0001C13 16.1047 13.8954 17.0001 15 17.0001C16.1046 17.0001 17 16.1047 17 15.0001ZM16.5 7.0001C16.5 7.8285 15.8284 8.5001 15 8.5001C14.1716 8.5001 13.5 7.8285 13.5 7.0001C13.5 6.1717 14.1716 5.5001 15 5.5001C15.8284 5.5001 16.5 6.1717 16.5 7.0001Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t6q869exz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1L19 1C21.2092 1 23 2.7908 23 5L23 19C23 21.2092 21.2092 23 19 23L11 23C8.7908 23 7 21.2092 7 19L7 5C7 2.7908 8.7908 1 11 1ZM19 15C19 12.7909 17.2091 11 15 11C12.7909 11 11 12.7909 11 15C11 17.2091 12.7909 19 15 19C17.2091 19 19 17.2091 19 15ZM17 15C17 16.1046 16.1046 17 15 17C13.8954 17 13 16.1046 13 15C13 13.8954 13.8954 13 15 13C16.1046 13 17 13.8954 17 15ZM16.5 7C16.5 6.1716 15.8284 5.5 15 5.5C14.1716 5.5 13.5 6.1716 13.5 7C13.5 7.8284 14.1716 8.5 15 8.5C15.8284 8.5 16.5 7.8284 16.5 7Z");
  stroke: none;
}

</style>
