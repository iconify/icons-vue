<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8kkj974f"/><path clip-rule="evenodd" class="dmhpyvbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-pen-fill" /></template>
<style>
.d8kkj974f {
  d: path("M12 3H6C4.343 3 3 4.343 3 6V21L7 17H18C19.657 17 21 15.657 21 14V12");
}

.dmhpyvbnt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.263 9.626L15.832 12.057C15.736 12.153 15.622 12.228 15.496 12.279L11.371 13.929C11.253 13.976 11.127 14 11 14C10.448 14 10 13.552 10 13C10 12.873 10.024 12.747 10.071 12.629L11.721 8.504C11.772 8.378 11.847 8.264 11.943 8.168L17.305 2.806C18.379 1.731 20.121 1.731 21.194 2.805C22.269 3.879 22.269 5.621 21.194 6.695L18.263 9.626Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
