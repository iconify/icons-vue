<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zryw3f5rf"/><path class="hvef7bbwl"/><g class="o86-og0pq"><path class="z-9gsrb3c"/><path class="u1r72ccmo"/></g><path class="n_0bfo-pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:outbox-tray" /></template>
<style>
.hvef7bbwl {
  fill: var(--svg-color--d1d2d3, #d1d2d3);
  d: path("M1.299 44.511v18.521c0 .489.409.904.897.904h59.62a.91.91 0 0 0 .902-.904V44.511z");
}

.n_0bfo-pw {
  fill: var(--svg-color--de374b, #de374b);
  d: path("M34.415 1.115c1.506 1.858 2.999 3.717 4.506 5.576a2240 2240 0 0 0 4.495 5.576c1.058 1.311-.285 3.01-2.421 3.01h-4.596v14.328h-8.782V15.277H23.01c-2.119 0-3.466-1.702-2.413-3.01c3-3.717 6-7.435 8.991-11.152c1.051-1.299 3.788-1.299 4.827 0");
}

.o86-og0pq {
  fill: var(--svg-color--405967, #405967);
}

.u1r72ccmo {
  d: path("M43.695 44.754c0 7.02-5.234 12.726-11.679 12.726c-6.453 0-11.681-5.7-11.681-12.726c0-7.03 5.228-12.729 11.681-12.729c6.444 0 11.679 5.695 11.679 12.729");
}

.z-9gsrb3c {
  d: path("M8.762 46.271h46.494c.387 0 .703-.271.703-.588V7.968c0-.319-.316-.587-.703-.587H8.767c-.207 0-.373.061-.477.159c0 0-.011.008-.018.017c0 0-.012.004-.02.019a.49.49 0 0 0-.188.393v37.714c0 .317.322.588.703.588");
}

.zryw3f5rf {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
  d: path("M2.197 63.937h59.619a.91.91 0 0 0 .9-.904V5.073c0-.493-.405-.9-.9-.9H2.195a.83.83 0 0 0-.614.241s-.013.013-.016.025c0 0-.02.008-.029.033a.8.8 0 0 0-.244.601v57.955c0 .489.411.904.902.904");
}

</style>
