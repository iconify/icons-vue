<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm4u6bc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slide-library-sharp" /></template>
<style>
.wm4u6bc-i {
  fill: currentColor;
  d: path("M2 20V7h2v11h14v2zm4-4V4h9.4l-2 2H8v8h12V8.6l2-2V16zm7.5-4q-.575 0-1.112-.262T11.5 11q.425 0 .713-.288T12.5 10q0-.625.438-1.062T14 8.5t1.063.438T15.5 10q0 .825-.587 1.413T13.5 12m3.275-3L15 7.225L19.45 2.8l1.75 1.75z");
}

</style>
