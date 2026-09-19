<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c95ulnmen"/><path class="eea1me72c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:wine-glass" /></template>
<style>
.c95ulnmen {
  fill: var(--svg-color--961623, #961623);
  d: path("M15.1 22.1C16 30.1 23.3 37 32 37c9.4 0 17.1-8 17.1-16.7v-.2c-9.8-1.3-22.1 5.8-34 2");
}

.eea1me72c {
  fill: var(--svg-color--a1b8c7, #a1b8c7);
  d: path("M54 20.4C54 9 48.3 2 48.3 2H15.7S10 9.1 10 20.4c0 10.8 9.3 20.9 20.9 21.5c-.1 6.3-.7 12.8-2.2 15.1c-2.2 3.2-9.8 1.6-9.8 5h26.2c0-3.4-7.6-1.8-9.8-5c-1.5-2.3-2.1-8.8-2.2-15.1C44.7 41.3 54 31.3 54 20.4M32 39.3c-9.8 0-17.9-7.8-18.9-16.7c-.1-.6-.1-1.3-.1-1.9c0-9.9 4.9-15.9 4.9-15.9h28.2s4.8 6 4.9 15.7v.2c0 9.6-8.5 18.6-19 18.6");
  opacity: var(--svg-opacity--0-8, 0.8);
}

</style>
