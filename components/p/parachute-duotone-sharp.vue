<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bfchbibob"/><path class="b9dcgf9fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parachute-duotone-sharp" /></template>
<style>
.b9dcgf9fp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9c0-4 4-6 9-6s9 2 9 6q-4.5-3-9 0q-4.5-3-9 0m0 0l9 9l9-9m-9 0v12m-3 0h6");
}

.bfchbibob {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.847 5.858c.553-.914 1.348-1.652 2.254-2.21C7.12 2.406 9.662 2 12 2s4.88.406 6.899 1.648c.906.558 1.701 1.296 2.254 2.21C21.725 6.806 22 7.895 22 9a1 1 0 0 1-1.555.832C19.274 9.052 17.924 8.5 16.5 8.5s-2.774.552-3.945 1.332a1 1 0 0 1-1.11 0C10.274 9.052 8.924 8.5 7.5 8.5s-2.774.552-3.945 1.332A1 1 0 0 1 2 9c0-1.105.275-2.194.847-3.142");
}

.ft5dv1b6b {
  fill: none;
}

</style>
