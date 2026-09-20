<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vmd11-b1o"/><path class="ejvonsxwj"/><circle class="vhsvn20ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:whale" /></template>
<style>
.ejvonsxwj {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M30.214 31.812c.149-.165.289-.338.429-.511c1.879-2.351 2.902-5.349 3.355-8.29C31.999 28.008 30.992 33 20 33C9 33 5 20 0 22c0 2 3 13.969 21 13.969c2 0 5.243-.664 8-2.969a12 12 0 0 0 1.214-1.188");
}

.vhsvn20ot {
  cx: 6.5px;
  cy: 21.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.vmd11-b1o {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 7.001c-2 3-2-1-5 2c-3-2-3 3-6 0c.899 2.699 3.419 4.574 6.1 4.926c-.277 1.789.202 3.946-2.1 6.073c-2.008 1.857-3.023.312-8-2.999c-3-1.996-5-4-10-3C5.117 15.178 0 20 0 22s3 13.969 21 13.969c2 0 5.243-.664 8-2.969c5.955-4.978 5.882-15.349 4.58-19.456C35.36 12.417 36 9.394 36 7.001");
}

</style>
