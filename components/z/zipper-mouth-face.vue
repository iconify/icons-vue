<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fk7h4w__g"><path class="skyqkrbeg"/><path class="t4a87sbvx"/></g><g class="fbp0m0b1e"><circle class="gnpfz2yrf"/><circle class="x96v6v8ju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:zipper-mouth-face" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.fk7h4w__g {
  fill: var(--svg-color--696a6b, #696a6b);
}

.gnpfz2yrf {
  cx: 20.5px;
  cy: 29px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.skyqkrbeg {
  d: path("m47.9 43.9l-4 4q-.3.3 0 .6l9.6 11.4c.1.1.4.2.5 0l5.9-5.9q.3-.3 0-.6l-11.4-9.6c-.2-.1-.4-.1-.6.1m9.8 9.7c.1.1.1.4 0 .5L54 57.7c-.1.1-.4.1-.5 0L50.3 54l3.6-3.6z");
}

.t4a87sbvx {
  d: path("M47.6 42h-3.2c-.2 0-.4.2-.4.4v2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v-2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v-2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v-2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v2c0-.2-.2-.4-.4-.4h-3.2c-.2 0-.4.2-.4.4v5.3c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v-2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v-2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v-2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v-2c0 .2.2.4.4.4h3.2c.2 0 .4-.2.4-.4v-5.3c0-.2-.2-.4-.4-.4");
}

.x96v6v8ju {
  cx: 43.5px;
  cy: 29px;
  r: 5px;
}

</style>
