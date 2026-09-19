<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="dxxaazbup"/><path class="c1y7jbc0z"/><path class="ar_6kcopg"/><path class="xym7j5z1d"/><path class="d9u238tjk"/><path class="si0532bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:tired-face" /></template>
<style>
.ar_6kcopg {
  fill: var(--svg-color--4c3526, #4c3526);
  d: path("M39 43.2c0-3.1-3-4.9-4.8-4.9c-.7 0-1.7.6-1.3 2.1c.2.8 1.4 1.7 1.4 3c0 2.5-4.4 2.5-4.4 0c0-1.3 1.2-2.2 1.4-3c.4-1.5-.7-2.1-1.3-2.1c-1.8 0-4.8 1.9-4.8 4.9c0 1.9 1 3.4 2.5 4.6h9c1.3-1.2 2.3-2.7 2.3-4.6");
}

.c1y7jbc0z {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M32 32c-8.8-.1-15.9 5.4-16 12.3c0 3.8 1.3 9.5 5.6 9.5c3.1 0 6.5-3.8 10.4-3.8s7.1 4 10.2 4c3.8 0 5.8-5.7 5.8-9.5c.1-6.8-7.2-12.4-16-12.5");
}

.d9u238tjk {
  fill: var(--svg-color--fff, #fff);
  d: path("M41.8 37c-2.5-1.9-5.7-3-9.8-3s-7.3 1.2-9.8 3c-.4.3-.4 1 .3 1h18.8c.8 0 .8-.7.5-1");
}

.dxxaazbup {
  fill: var(--svg-color--917524, #917524);
  d: path("M38.4 11.2c3.2 2.7 7.5 3.9 11.7 3.1c.6-.1 1.1 2 .4 2.2c-4.8.9-9.8-.5-13.5-3.6c-.5-.5 1-2 1.4-1.7m-24.5 3c4.2.7 8.5-.4 11.7-3.1c.4-.4 2 1.2 1.4 1.7c-3.7 3.2-8.7 4.5-13.5 3.6c-.7-.2-.2-2.3.4-2.2");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.si0532bho {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M51.7 21.1c.6.3.3 1-.2 1.1c-2.7.4-5.5.9-8.3 2.4c4 .7 7.2 2.7 9 4.8c.4.5-.1 1.1-.5 1c-4.8-1.7-9.7-2.7-15.8-2c-.5 0-.9-.2-.8-.7c1.6-7.3 10.9-10 16.6-6.6m-39.4 0c-.6.3-.3 1 .2 1.1c2.7.4 5.5.9 8.3 2.4c-4 .7-7.2 2.7-9 4.8c-.4.5.1 1.1.5 1c4.8-1.7 9.7-2.7 15.8-2c.5 0 .9-.2.8-.7c-1.6-7.3-10.9-10-16.6-6.6");
}

.xym7j5z1d {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M32 46c-6 0-8 5-8 5s4-3 8-3s8 3 8 3s-2-5-8-5");
}

</style>
