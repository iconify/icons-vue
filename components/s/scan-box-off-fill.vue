<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="adzb2xnfh"/><path class="x1l-5kqmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-off-fill" /></template>
<style>
.adzb2xnfh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 17C11.844 17 11.689 16.964 11.546 16.891L7.546 14.854C7.211 14.684 7 14.339 7 13.963V10.037C7 9.844 7.055 9.66 7.154 9.503L12 12V17Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x1l-5kqmk {
  d: path("M3 8V6C3 5.172 3.336 4.422 3.879 3.879M20.121 20.121C19.578 20.664 18.828 21 18 21H16M8 21H6C4.343 21 3 19.657 3 18V16M16 3H18C19.657 3 21 4.343 21 6V8M7.154 9.503L12 12V17C11.845 17 11.689 16.964 11.546 16.891L7.546 14.854C7.211 14.684 7 14.339 7 13.963V10.037C7 9.661 7.211 9.316 7.546 9.146L8.606 8.606M13.089 7.432L16.454 9.146C16.789 9.316 17 9.661 17 10.037V11.343M2 2L22 22");
}

</style>
