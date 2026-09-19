<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quqpx_bfe"/><path class="v33l7uims"/><path class="rway2ozvh"/><path class="ckasmk93q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mail-lock" /></template>
<style>
.ckasmk93q {
  fill: currentColor;
  d: path("M23 15v-1c0-1.1-.9-2-2-2s-2 .9-2 2v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-3 0v-1c0-.55.45-1 1-1s1 .45 1 1v1z");
}

.quqpx_bfe {
  fill: currentColor;
  d: path("M20 6H4l8 5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rway2ozvh {
  fill: currentColor;
  d: path("M4 18V8l8 5l8-5v2.08c.32-.07.66-.1 1-.1h1V6c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h12v-2zM20 6l-8 5l-8-5z");
}

.v33l7uims {
  fill: currentColor;
  d: path("M12 13L4 8v10h12v-3.03a5 5 0 0 1 4-4.9V8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
