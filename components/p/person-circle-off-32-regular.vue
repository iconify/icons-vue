<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hihmj_erd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-32-regular" /></template>
<style>
.hihmj_erd {
  fill: currentColor;
  d: path("M2.293 2.293a1 1 0 0 1 1.414 0l26 26a1 1 0 1 1-1.414 1.414l-3.127-3.127A13.94 13.94 0 0 1 16 30C8.268 30 2 23.732 2 16c0-3.506 1.288-6.712 3.418-9.168L2.293 3.707a1 1 0 0 1 0-1.414m4.545 5.959A11.95 11.95 0 0 0 4 16c0 6.627 5.373 12 12 12c2.954 0 5.656-1.07 7.746-2.84l-2.554-2.554C19.912 23.805 18.062 24.5 16 24.5c-3.866 0-7-2.428-7-6.071A2.43 2.43 0 0 1 11.429 16h3.157zM16 2c7.732 0 14 6.268 14 14c0 2.962-.921 5.708-2.491 7.97l-1.444-1.442A11.94 11.94 0 0 0 28 16c0-6.627-5.373-12-12-12c-2.409 0-4.65.712-6.53 1.934L8.028 4.49A13.94 13.94 0 0 1 16 2m4.571 14A2.43 2.43 0 0 1 23 18.429q-.002.494-.077.957L19.538 16zM16 7a3.75 3.75 0 0 1 1.653 7.115l-5.02-5.02A3.75 3.75 0 0 1 16 7");
}

</style>
