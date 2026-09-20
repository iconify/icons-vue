<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fcpj8-kyj"/><path class="d2r9r40jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:tooth" /></template>
<style>
.d2r9r40jn {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M18 7.259c-2.278 0-4.419-.81-5.444-1.563a.75.75 0 1 1 .887-1.209c.84.617 2.722 1.273 4.556 1.273c1.97 0 3.942-.709 4.489-1.217a.75.75 0 0 1 1.021 1.099c-.958.891-3.431 1.617-5.509 1.617");
}

.fcpj8-kyj {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M18 2C13 2 11.11-1.276 7.002.7C3 2.625 7 17.002 9 20c-.444 2.537-.59 8.787-.171 10.91c.576 2.921 1.561 5.09 2.748 5.09c2 0 2.423-13.002 6.423-13zm0 0c5 0 6.89-3.276 10.998-1.3C33 2.625 29 17.002 27 20c.444 2.537.59 8.787.171 10.91c-.575 2.921-1.561 5.09-2.748 5.09c-2 0-2.423-13.002-6.423-13z");
}

</style>
