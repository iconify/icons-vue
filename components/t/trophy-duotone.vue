<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzxhvcg1u"/><path class="am_64dmky"/><path class="l2g80cb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trophy-duotone" /></template>
<style>
.am_64dmky {
  fill: currentColor;
  d: path("M15 1C17.2092 1 19 2.79094 19 5V9C19 12.866 15.866 16 12 16C8.13402 16 5 12.866 5 9V5C5 2.79092 6.79092 1 9 1H15Z");
  stroke: none;
}

.l2g80cb3z {
  d: path("M9 19H15C16.6569 19 18 20.3432 18 22H6C6 20.3432 7.3432 19 9 19Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzxhvcg1u {
  stroke-opacity: 0.4;
  d: path("M6 5H4C2.8954 5 2 5.8954 2 7V9C2 10.1046 2.8954 11 4 11H6M18 5H20C21.1046 5 22 5.8954 22 7V9C22 10.1046 21.1046 11 20 11H18M12 15V19");
}

</style>
