<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8amjybjo"/><path class="a9dq9bw7h"/><path class="d5ony8e-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mic" /></template>
<style>
.a9dq9bw7h {
  fill: currentColor;
  d: path("M12 14c1.66 0 3-1.34 3-3V5c0-1.66-1.34-3-3-3S9 3.34 9 5v6c0 1.66 1.34 3 3 3m-1-9c0-.55.45-1 1-1s1 .45 1 1v6c0 .55-.45 1-1 1s-1-.45-1-1z");
}

.d5ony8e-t {
  fill: currentColor;
  d: path("M17 11c0 2.76-2.24 5-5 5s-5-2.24-5-5H5c0 3.53 2.61 6.43 6 6.92V21h2v-3.08c3.39-.49 6-3.39 6-6.92z");
}

.o8amjybjo {
  fill: currentColor;
  d: path("M12 12c.55 0 1-.45 1-1V5c0-.55-.45-1-1-1s-1 .45-1 1v6c0 .55.45 1 1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
