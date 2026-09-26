<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="nzdbp6bcl"/><path class="l4n1qbbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:replay-fill" /></template>
<style>
.l4n1qbbmd {
  d: path("M20.7883 10.0593C20.929 10.6966 21 11.3473 21 12C21 16.9706 16.9706 21 12 21C7.0294 21 3 16.9706 3 12C3 7.0294 7.0294 3 12 3C14.4831 3 16.8559 4.0259 18.5568 5.8349M19.7143 3L19.2707 6.105C19.2317 6.3784 18.9784 6.5683 18.705 6.5293L15.6 6.0857");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzdbp6bcl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.962734 9.105541C7.962734 7.53467 9.690636 6.576985 11.022732 7.409545L16.332265 10.728003C17.272267 11.315504 17.272267 12.684496 16.332265 13.271998L11.022732 16.590456C9.690636 17.423016 7.962734 16.465331 7.962734 14.89446Z");
  stroke: none;
}

</style>
