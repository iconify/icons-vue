<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f0j9ryxke"/><path class="b3lapab3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-bulk" /></template>
<style>
.b3lapab3s {
  d: path("M9 13h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6.106 4.447l-2 4a1 1 0 1 1-1.788-.894l2-4a1 1 0 1 1 1.788.894m8-.894l2 4a1 1 0 1 1-1.788.894l-2-4a1 1 0 1 1 1.788-.894");
}

.cuyn6tgcc {
  fill: currentColor;
}

.f0j9ryxke {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 18H7a3 3 0 0 1-3-3V7c0-1.039.578-1.992 1.293-2.707l1-1C7.008 2.578 7.961 2 9 2h6c1.039 0 1.992.578 2.707 1.293l1 1C19.422 5.008 20 5.961 20 7v8a3 3 0 0 1-3 3M6 9h12V6.828a1 1 0 0 0-.293-.707l-1.828-1.828A1 1 0 0 0 15.172 4H8.828a1 1 0 0 0-.707.293L6.293 6.121A1 1 0 0 0 6 6.828Z");
}

</style>
